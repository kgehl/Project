# Determine N<sub>2</sub>O Flux from Sorghum Cropping Systems in the Great Plains
---
**Author**: Kathy Gehl </br>
**Semester**: Spring 2019 </br>



## Objective
---
Create a Python code to organize N<sub>2</sub>O gas measurements and calculate daily N<sub>2</sub>O flux values.

- **Necessary steps**
   - Import raw .csv output files from gas chromotograph (N<sub>2</sub>O data)
   - Reorganize the N<sub>2</sub>O data into a workable dataframe
   - Calculate daily N<sub>2</sub>O flux for each plot at each sampling event
        * Flux will be calculated as slope using linear regression with the time sequence as the x variable and N<sub>2</sub>O values as the y variable.

## Motivation
---

* **Background and Rationale**

    - Study sites have been established in Colby, KS and Goodwell, OK to quantify N<sub>2</sub>O emissions from fields/plots planted to grain sorghum. This project generates a large amount of N<sub>2</sub>O gas measurements over the growing season.
    - Each sampling event is sampled over a time sequence of 0, 15, 30, and 45 minutes. Measured N<sub>2</sub>O concentrations are linearly regressed against the time sequence and the slope is considered the N<sub>2</sub>O flux for that plot on each sampling date. Linear extrapolation is used to estimate flux between sampling points and then season-long emissions are estimated.
    - We currently have been performing these calculations in Excel, but having a code in place would streamline the process and would help reduce human errors from copying, pasting, and deleting within the spreadsheet.
    

 
## Outcomes
---

The desired outcomes for this proposed code are:

- Successful import of gas sample measurements
- Removal of data values not needed (check samples)
- Linear regression calculations for each plot over a time series to estimate daily N<sub>2</sub>O flux as slope.


## Sketch

<img src="Sketch_final.jpg" alt="sketch_image" width="600"/>


