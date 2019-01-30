
# Inplementing and optimize antecedent precipitation model (API) in python

**Name**: Pedro Rossini <br/>
**Semester**: Spring 2019 <br/>
**Project area**: Agronomy


## Objective
Write a python function to automate the calculation of daily growing degree days using maximum and minimum daily air temperature.

## Outcomes
I want the function to produce a .csv file with four columns: day, month, year, degree days

## Rationale
Crop phenology is largely modulated by temperature. Growing degree day (GDD) is a way to keep track of physiological time independently of the calendar time, which is practical for predicting phenological stages using readily available temperature. For this reason, GDD is also called thermal time. In simple terms, growing degree days is basically the computation of cumulative temperature over a specific minimum threshold temperature value dictated by the physiology of each crop. 

Our lab is currently collecting large files of air temperature data from field experiments that need to be summarized by hand, which is time consuming and tedius. Thus, my goal is to automate this process using python.

## Sketch

<img src="sketch.jpg" alt="sketch_image" width="500"/>

## References
McMaster, G.S. and Wilhelm, W.W., 1997. Growing degree-days: one equation, two interpretations. Agricultural and forest meteorology, 87(4), pp.291-300.

