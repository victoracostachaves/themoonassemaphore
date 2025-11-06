# themoonassemaphore
User Guide: Amphibian Occupancy Modeling Analysis
Acosta Chaves et al. The Moon as Semaphore: Occupancy Modeling Reveals Contrasting Lunar Responses in Elusive Terraranas of a Tropical Montane Forest

1. Data File

File: especies_modelos_RM.xlsx

Contents:

Species data (especies): Diasporus diastema (diastema), Pristimantis cruentus (cruentus), Pristimantis caryophyllaceus (caryophyllaceus)

Site information (sitio)

Occupancy records

Environmental covariates:

Tree diameter (DBH, dap)

Tree richness (treeR)

Tree abundance (treeA)

Temperature (temp)

Relative humidity (hum)

Absolute humidity is estimated with code, and then a data table will be created, with a formula based on temperature and relative humidity*

2. Analysis Code

All R scripts are built specifically for this dataset

Code references the exact column names and structure in the Excel file

3. R Scripts

Primary analyses: Occupancy and detection probability estimation for three focal species

Supplementary code: Figure generation and visualization (includes unpublished analyses for visualization)

Scripts are organized by analytical purpose

4. Setup Instructions

Create project folder: ecologyandevolution on your desktop

Initialize R Project within this folder

Install required R packages (list provided in scripts)

Important: Update file paths in scripts to point to your local data directory before execution

Note: Ensure all file path references are corrected for your local system configuration before running any scripts.
This code was originally modified from Barrantes-Madrigal, J., M. S. Parallada, G. Alvarado, and V. J. Acosta-Chaves. 2022. “Occupancy and Probability of Detection of the Introduced Population of Eleutherodactylus coqui in Turrialba, Costa Rica.” Acta Herpetologica 17, no. 2: 177–186. https://doi.org/10.36253/a_h-132092, using the IA model named "DeepSeek" (free). 
