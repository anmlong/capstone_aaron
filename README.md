# capstone_aaron
 Aaron's capstone project

## **About the data**

I will be analyzing the raw data from the paper entitled *Development of machine learning models for diagnosis of glaucoma.* This analysis looks at trends in glaucoma samples and healthy samples. 

I first looked at the paper and defined some of the key terms and looked up some normal values for the columns. I was interested in looking at glaucoma patients who have normal readings in some of the tests. I first looked to see if any glaucoma samples had normal readings in both ocular_pressure over and a mean deviation. 


#A meaningful title and brief (markdown) introduction to each report.

Question 1 and 2 are  ipython notebook (report_python.ipynb) and question 3 is a markdown (report_r.Rmd).

I will be analyzing the raw data from the paper entitled *Development of machine learning models for diagnosis of glaucoma.* This analysis will help answer three questions. I first looked at the paper and defined some of the key terms and looked up some normal values for the columns. I was interested in looking at glaucoma patients who have normal readings in some of the tests. I first looked to see if any glaucoma samples had normal readings in both ocular_pressure over and a mean deviation. 


#Appropriate questions include performing data filtering/assessment/grouping followed by summary statistics/machine learning and assessing patterns using data visualization. Please note:

#I used https://pandas.pydata.org, https://stackoverflow.com, and the lectures for problem solving.

### **Question 1.**
ocular_pressure over 22 and a mean deviation (MD) below -2.0 are considered to be abnormal. Do all the glaucoma patients show both of these abnormlities? How many of them have normal ocular pressure and MD values? Show scatter plots of different stages of the analysis. 


### **Question 2.** 
Looking at the glaucoma group that had normal ocular pressure and MD values from question 1, are there any unique trends compared to the rest of the glaucoma samples? Are these samples more like the healthy samples than the glaucoma samples? are there any columns that seem to be predictors of glaucoma? Is age a predictor? do any trends change with age?
 

### **Question 3.** 
From question 2 we know the mean age of glaucoma samples is around 9 years higher than healthy samples. Are there any other trends with age? Show these trends graphically.


### **descriptions of the columns in the data sets**
**RNFL4.mean** - the mean of the retinal nerve fiber layer (RNFL) thickness. The paper says it reflects mean of SUP-INF-TMP combination (SUP=superior; NAS=nasal; INF=inferior)

**cornea_thickness**- Many times, patients with thin corneas (less than 555 µm) show artificially low IOP readings. This is dangerous because if your actual IOP is higher than your reading shows, you may be at risk for developing glaucoma and your doctor may not know it. (www.glaucoma.org)

**GHT**- glaucoma hemifield test is an indicator of differences between the superior and inferior hemifields. (www.reviewofoptometry.com)

**PSD**- pattern standard deviation (PSD) reflects the degree of departure (difference) of the measured VF pattern (shape) from the normal hill of vision. A small PSD reflects a smooth uniform hill of vision, while a large PSD value reflects an irregular hill of vision. (PMCID: PMC3678209)

**MD**- Mean deviation (MD) is the average difference from normal expected value in the patients' particular age group. Typically, an MD of -2.00 or less could indicate glaucoma. (glaucomatoday.com)

**ocular_pressure**- Eye pressure is measured in millimeters of mercury (mm Hg). Normal eye pressure ranges from 12-22 mm Hg, and eye pressure of greater than 22 mm Hg is considered higher than normal.(www.glaucoma.org)

**glaucoma**-is a group of eye conditions that damage the optic nerve. It is often caused by an abnormally high pressure in your eye (www.mayoclinic.org)

**R**L-They are Latin abbreviations: OS (oculus sinister) means the left eye and OD (oculus dextrus) means the right eye (www.webmd.com)

### **description of data sets** 
ds_test.csv - 100 cases of data
ds_train.csv - 399 cases of data as training and validation
ds_whole.csv - all 499 cases together. I exclusivly looked at this data set
