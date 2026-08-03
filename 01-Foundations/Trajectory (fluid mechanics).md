---
title: "Trajectory (fluid mechanics)"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Trajectory_(fluid_mechanics)"
wikipedia_categories: ["Continuum mechanics", "Fluid dynamics", "Meteorological concepts", "Numerical analysis", "Numerical climate and weather models"]
related: ["[[Sheet metal forming simulation]]", "[[2Sum]]", "[[Abramowitz and Stegun]]", "[[Adaptive step size]]", "[[Adjoint state method]]", "[[Affine arithmetic]]", "[[Applied element method]]", "[[Approximation]]", "[[Approximation error]]", "[[Approximation theory]]"]
---

# Trajectory (fluid mechanics)

In fluid mechanics, meteorology (weather) and oceanography, a trajectory traces the motion of a single point, often called a parcel, in the flow. 
Trajectories are useful for tracking atmospheric contaminants, such as smoke plumes, and as constituents to Lagrangian simulations, such as contour advection or semi-Lagrangian schemes.
Suppose we have a time-varying flow field, 
  
    
      
        
          
            
              v
              →
            
          
        
        
          
            
              x
              →
            
          
        
        ,
         
        t
      
    
    
  
. The motion of a fluid parcel, or trajectory, is given by the following system of ordinary differential equations:

  
    
      
        
          
            
              d
              
                
                  
                    x
                    →
                  
                
              
            
            
              d
              t
            
          
        
        
          
            
              v
              →
            
          
        
        
          
            
              x
              →
            
          
        
        ,
         
        t
      
    
    
  

While the equation looks simple, there are at least three concerns when attempting to solve it numerically.  The first is the integration scheme. This is typically a Runge-Kutta, although others can be useful as well, such as a leapfrog.  The second is the method of determining the velocity vector, 
  
    
      
        
          
            
              v
              →
            
          
        
      
    
    
  
 at a given position, 
  
    
      
        
          
            
              x
              →
            
          
        
      
    
    
  
, and time, t. Normally, it is not known at all positions and times, therefore some method of interpolation is required.  If the velocities are gridded in space and time, then bilinear, trilinear or higher-dimensional linear interpolation is appropriate. Bicubic, tricubic, etc., interpolation is used as well, but is probably not worth the extra computational overhead.
Velocity fields can be determined by measurement, e.g. from weather balloons, from numerical models or especially from a combination of the two, e.g. assimilation models.
The final concern is metric corrections.  These are necessary for geophysical fluid flows on a spherical Earth.  The differential equations for tracing a two-dimensional, atmospheric trajectory in longitude-latitude coordinates are as follows:

  
    
      
        
          
            
              d
              θ
            
            
              d
              t
            
          
        
        
          
            u
            
              r
               
              ϕ
            
          
        
      
    
    
  

  
    
      
        
          
            
              d
              ϕ
            
            
              d
              t
            
          
        
        
          
            v
            r
          
        
      
    
    
  

where, 
  
    
      
        θ
      
    
    
  
 and 
  
    
      
        ϕ
      
    
    
  
 are, respectively, the longitude and latitude in radians, r is the radius of the Earth, u is the zonal wind and v is the meridional wind.
One problem with this formulation is the polar singularity: notice how the denominator in the first equation goes to zero when the latitude is 90 degrees—plus or minus.  One means of overcoming this is to use a locally Cartesian coordinate system close to the poles.  Another is to perform the integration on a pair of Azimuthal equidistant projections—one for the N. Hemisphere and one for the S. Hemisphere.
Trajectories can be validated by balloons in the atmosphere and buoys in the ocean.

## Related

- [[Sheet metal forming simulation]]
- [[2Sum]]
- [[Abramowitz and Stegun]]
- [[Adaptive step size]]
- [[Adjoint state method]]
- [[Affine arithmetic]]
- [[Applied element method]]
- [[Approximation]]
- [[Approximation error]]
- [[Approximation theory]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Trajectory_(fluid_mechanics)