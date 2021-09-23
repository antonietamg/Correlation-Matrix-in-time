# Correlation-Matrix-in-time
Multivariate Correlation Analysis in Time. Based on the work of Christian Rummel, Gerold Baier and Markus Müller (2007)
https://doi.org/10.1016/j.jneumeth.2007.06.023

BY: ANTONIETA MARTÍNEZ-GUERRERO & DAVID E. APABLAZA YEVENES
We will appreciate if you refer to the authors of this code and the article of Rummel et al. (2007)

This code is in development. Please follow the instructions to make it work.

1. Download the file tree.zip 
2. Unzip the file.
3. Put the file in the path of your preference.
4. Go to the MC_Analysis folder and read the README file. Follow the instructions to build your folder tree.
5. Open the MC_Matrix.R script in RStudio and run the function Run_Win 
6. Create the DatsFile.csv. Download and open the DatsFile.csv example in this repository to see hoy to fill the columns.
7. Change manually the parameters in PARAMETERS 1. "general_path" is the path where you placed your folder tree. The "Dats_File" object is the DatsFile.csv
8. Change manually the parameters in PARAMETER 2. Every parameter is commented.
9. To calculate Correlation Matrices in time and the Mean Correlation Matrix: Run from "for(index_xx in 1:length(na.omit(Dats_File$sujeto))){" This line is above PARAMETERS 2.
10. To calculate the Stationary Pattern run from ##### START STATIONARY PATTERN C #####
11. To calculate the deviations and fluctuations from the Stationary Pattern, run from #### START DEVIATIONS C ####

To get the Stationary Pattern, first you need to run the Correlation matrices in time and the Mean Correlation Matrix. In order to get the deviations and the fluctuations from the Stationary pattern, you need to run all the whole above.
