# project
# First draft 

# Implementing an exponential filter model to estimate soil moisture in the entire root-zone

**Name**: Pedro Rossini <br/>
**Semester**: Spring 2019 <br/>
**Project area**: Agronomy


## Objective

Estimate soil water content of the entire root-zone from surface observations using an exponential filter model

## Outcomes

I would like to predict the soil moisture in the entire profile (0 to 80 cm) from soil moisture mesurements at surface (o to 15 cm) depth.


## Rationale

Accurate measurement of soil water content is critical to accomplishing sustainable and high-performance irrigation farming. Local observations of soil moisture at multiple-depth are considered one of the best alternatives to track root-zone soil water moisture but it is hard to implement in productions fields. An innovative alternative to tackle this is using field observations from a single sensor at the surface (0-15cm) and predict the entire root-zone moisture though an exponential filter model.

Exponential filter model is a semi-mechanistic model to estimate soil water index (SWI) of the root-zone from the soil observations at the surface. The model present only 3 parameters, SWISURF that represent the soil moisture observet at the surface, SURFMAX that represent the maximum amount of water that the surface can hold and K is a parameter that range between 0 to 1 and is realted to the gaps between observations.

<br/>
<img src="SWI_eq.JPG" alt="sketch_image" width="500"/>
<br/>
 

Available soil moisture data from Kansas Mesonet and field experiments will be used to training and validating the model.

## Sketch
 
<img src="Soil_2.JPG" alt="sketch_image" width="500"/>

## References
Albergel, Clément, et al. "From near-surface to root-zone soil moisture using an exponential filter: an assessment of the method based on in-situ observations and model simulations." Hydrology and Earth System Sciences 12.6 (2008): 1323-1337.




