---
title: "TP model transformation in control theory"
tags: ["cs", "general-cs", "intermediate"]
domain: General CS
level: intermediate
source: "https://en.wikipedia.org/wiki/TP_model_transformation_in_control_theory"
wikipedia_categories: ["Control theory"]
related: ["[[4D-RCS Reference Model Architecture]]", "[[Ackermann's formula]]", "[[Active disturbance rejection control]]", "[[Adaptive control]]", "[[Advanced process control]]", "[[Affect control theory]]", "[[American Automatic Control Council]]", "[[Anticausal system]]", "[[Artstein's theorem]]", "[[Asymptotic gain model]]"]
---

# TP model transformation in control theory

Baranyi and Yam proposed the TP model transformation as a new concept in quasi-LPV (qLPV) based control, which plays a central role in the highly desirable bridging between identification and polytopic systems theories. It is also used as a TS (Takagi-Sugeno) fuzzy model transformation. It is uniquely effective in manipulating the convex hull of polytopic forms (or TS fuzzy models), and, hence, has revealed and proved the fact that convex hull manipulation is a necessary and crucial step in achieving optimal solutions and decreasing conservativeness in modern linear matrix inequality based control theory. Thus, although it is a transformation in a mathematical sense, it has established a conceptually new direction in control theory and has laid the ground for further new approaches towards optimality.
For details please visit: TP model transformation.

TP-tool MATLAB toolbox

A free MATLAB implementation of the TP model transformation can be downloaded at  or an old version of the toolbox is available at  MATLAB Central . Be careful, in the MATLAB toolbox the assignments of the dimensions of the core tensor is in the opposite way in contrast to the notation used in the related literature. In some variants of the ToolBox, the first two dimension of the core tensor is assigned to the vertex systems. In the TP model literature the last two. A simple example is given below.

clear
M1=20; 		% Grid density
M2=20;
omega1=[-1,1]; 		%Interval 
omega2=[-1,1];
domain=[omega1; omega2];

for m1=1:M1
    for m2=1:M2
        p1=omega1(1)+(omega1(2)-omega1(1))/M1*(m1-1); 	%sampling grid
        p2=omega2(1)+(omega2(2)-omega2(1))/M2*(m2-1);
        SD(m1,m2,1,:)=[1 0];				% SD is the discretized system matrix
        SD(m1,m2,2,:)=[(-1-0.67*p1*p1) (1.726*p2*p2)];
    end
    end

[S,U, sv]=hosvd(SD,[1,1,0,0],1e-12);		% Finding the TP structure
UA{1}=U{1};					% This is the HOSVD based canonical form
UA{2}=U{2};
ns1 = input('Results of SNNN TS fuzzy model');
UC=genhull(UA,'snnn'); 				% snnn weightinf functions
UCP{1}=pinv(UC{1});
UCP{2}=pinv(UC{2});
SC=tprods(SD,UCP);  				%This is to find  the core tensor 
H(:,:)=SC(1,1,:,:)                              %This is to show the vertices of the TP model
H(:,:)=SC(1,2,:,:)
H(:,:)=SC(2,1,:,:)
H(:,:)=SC(2,2,:,:)
figure(1) 
hold all 
plothull(U{1}, omega1)                          %Draw the waiting functions of p1
title('Weighting functions for p_{1}');
xlabel('p_{1}')
ylabel('Weighting functions')

grid on
box on

figure(2) 
hold all 
plothull(UC{2}, omega2)                         %Show the waiting functions of p2
title('Weighting functions for p_{2}');
xlabel('p_{2}')
ylabel('Weighting functions')

grid on
box on

ns2 = input('Results of CNO TS fuzzy model');
UC=genhull(UA,'cno');                          %Create CNO type waiting functions 
UCP{1}=pinv(UC{1});
UCP{2}=pinv(UC{2});
SC=tprods(SD,UCP);                             %Find the cortensor
H(:,:)=SC(1,1,:,:)                             %Show the vertices of the TP model
H(:,:)=SC(1,2,:,:)
H(:,:)=SC(2,1,:,:)
H(:,:)=SC(2,2,:,:)
figure(1) 
hold all 
plothull(U{1}, omega1)                         %Show the waiting functions of p1
title('Weighting functions for p_{1}');
xlabel('p_{1}')
ylabel('Weighting functions')

grid on
box on
figure(2) 
hold all 
plothull(UC{2}, omega2)                        %Show the waiting functions of p2
title('Weighting functions for p_{2}');
xlabel('p_{2}')
ylabel('Weighting functions')

	Once you have the feedback vertexes derived to each vertexes of the TP model then you may want to calculate the controller over the same polytope (see PDC design by Tanaka)
W = queryw1(UC,domain,p);  % computing the weighting values over the parameter vector
F = tprods(K,W);		% calculating the parameter dependent feedback F(p)
F = shiftdim(F)
U=-F*x				% calculate the control value.

## Related

- [[4D-RCS Reference Model Architecture]]
- [[Ackermann's formula]]
- [[Active disturbance rejection control]]
- [[Adaptive control]]
- [[Advanced process control]]
- [[Affect control theory]]
- [[American Automatic Control Council]]
- [[Anticausal system]]
- [[Artstein's theorem]]
- [[Asymptotic gain model]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/TP_model_transformation_in_control_theory