---
title: "Data cube"
tags: ["cs", "data-databases", "intermediate"]
domain: Data & Databases
level: intermediate
source: "https://en.wikipedia.org/wiki/Data_cube"
wikipedia_categories: ["Database theory", "Image processing"]
related: ["[[3D selfie]]", "[[Abel transform]]", "[[ActionShot]]", "[[Acutance]]", "[[Adaptive histogram equalization]]", "[[Albert Bijaoui]]", "[[Alpha to coverage]]", "[[Analog image processing]]", "[[Anisotropic diffusion]]", "[[Atkinson dithering]]"]
---

# Data cube

In computer programming, a data cube (or datacube) is a multi-dimensional array of values. Typically, the term "data cube" is applied in contexts where these arrays are massively larger than the hosting computer's main memory; examples include multi-terabyte/petabyte data warehouses and time series of image data.
Even though it is called a cube, a data cube generally is a multi-dimensional concept which can be 1-dimensional, 2-dimensional, 3-dimensional, or higher-dimensional.
The data cube is used to represent data (sometimes called facts) along some dimensions of interest.
In satellite image timeseries, dimensions would be latitude and longitude coordinates and time; a fact (sometimes called measure) would be a pixel at a given space and time as taken by the satellite.
For example, in online analytical processing, an OLAP cube about a company would have dimensions that could be the company subsidiaries, the company products, and time; in this setup, a fact would be a sales event where a particular product has been sold in a particular subsidiary at a particular time. 
In any case, every dimension divides data into groups of cells whereas each cell in the cube represents a single measure of interest. Sometimes cubes hold only a few values with the rest being empty, i.e. undefined, while sometimes most or all cube coordinates hold a cell value. In the first case such data are called sparse, and in the second case they are called dense, although there is no hard delineation between the two.
Data cubes may be stored in database management systems (DBMS) as part of array DBMS.
Spatio-temporal databases and geospatial databases may also be represented as coverage data.

## Related

- [[3D selfie]]
- [[Abel transform]]
- [[ActionShot]]
- [[Acutance]]
- [[Adaptive histogram equalization]]
- [[Albert Bijaoui]]
- [[Alpha to coverage]]
- [[Analog image processing]]
- [[Anisotropic diffusion]]
- [[Atkinson dithering]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Data_cube