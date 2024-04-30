#Sample Codebook Assignment

Changes made to the data set
- First transformed variable S003 in both EVS and WVS and turned into a numeric variable
- Created 15-17 variables from existing variables in each new data set created from WSV and ESV
- merged and created source id for each individual row
- filtered and mutated in names of countries into merged data set with id code provided by Hart
- relocated source id to designated spot
- removed NA's from each variable individually
- mutated across the columns to switch labels to factor labels
- mutated the month variable to show the month name rather than the number
- added a function variable for the purpose of displaying the rows when kabling in the codebook
- adjusted the function code to do row.number() instead of as.numeric