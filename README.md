# SCEC_2019
Repository for the 2019 Machine Learning team.  A place to host datasets, probabilities, and code.


### About this repo, and which folder to use in 2020 and beyond: 
The final files folder is a distilled compilation of everything needed to use and run the 2019 team's code / results.
Everything else was used prior to the creation of the final files folder. We kept the other folders the same for our convenience with not having to change url's in some of our code.  Moving forward we suggest working strictly out of the final files folder.

The models were built based on two separate interval/binning methods on 'eqdata_33_sections'.  The first one was open interval (ask Bill Savran), the second was a 100 year input bin, 30 year output bin. 
####  About the final files folder: 
###### Inside the pickled files folder are pickled models: 
1. Logistic Regression models (33 total)
2. Random Forest 
3. Neural Network
4. There's a CSV file for the baseline probabilities.  
###### About the datasets folder: 
1. 'eqdata_33_sections' is the base final, from which 'eqdata_33_sects_testing' and 'eqdata_33_sects_training' are a straight split of eqdata_33_sections. From there, the other training/testing files are made based on the two separate binning/interval interpretations mentioned above.  Namely the open interval, and the 100 year input / 30 year output sum interval method. As an example, 'eqdata_33_sections_30_year_intervals_testing' is the open interval testing set. 
2. Why some files are binary files: if you don't use the binary files, colab notebooks had some issues, so we had to make some binary files.  
#### Not found in this repo, but found in the google drive: 
* Code to build the ML models
* Code for generating probabilities
* Visualization tools (ROC curves, scoring plots, etc) 
* Results files
