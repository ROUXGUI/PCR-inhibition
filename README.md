# PCR-inhibition
Rmarkdown code including R code chunk for cleaning and analysis of a dataset of qPCR Cp results with inhibition controls.

This code is running with R 3.5.0 and RStudio 1.1.419

The first part of the part deals with Toxoplasma PCR, the second part deals with Pneumocystis PCR.
Each part contains database cleaning and tidying followed by descriptive analysis and statistical inductions.

The code was written to study raw datasets of cycle threshold (Ct) qPCR values, 
leucocytes blood counts and leucocytes cerebrospinal fluid counts of clinical samples.

Some parts of the code, such as graphical representation of Youden's Index in function of Ct cut-off value
run slowly, but they were sufficiently fast to our dataset.


