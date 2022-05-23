# Conventional-First-Lien-Loans
This project is to predict underwriting decisions for  conventional first lien loans in Tucson, Arizona.
> Prerequisites:

	 - [ ] Python (Anaconda distribution preferred)
	 - [ ] pandas
	 - [ ] numpy
	 - [ ] matplotlib
	 - [ ] statsmodels
	 - [ ] sklearn
  	 - [ ] scipy
  	 - [ ] time
   	 - [ ] datetime 

> Steps to implement and run the model

 1. Download the dataset from the link below and save it in a folder. 
 
    https://ffiec.cfpb.gov/data-browser/data/2020?category=msamds&items=46060&actions_taken=1,2,3
   
 2. Download the **Conventional First Lien Application.ipynb** jupyter notbook files and save it in the same folder as used in step 1.
   
 3. Run the **Conventional First Lien Application.ipynb** jupyter notebook file.

> Reviewing the results

 1. The jupyter notebook file runs two models and generates two results file given below
 
      **i.  Model_Results_With_Race_Sex_Age.xlsx**
      
      **ii. Model_Results_Without_Race_Sex_Age.xlsx**
 
 2. The **Model_Results_With_Race_Sex_Age.xlsx** file is a result of a model which includes Race, Sex and Age field and helps us in identifying Fair Lending issues associated
    with the model.
    
 3. The **Model_Results_Without_Race_Sex_Age.xlsx** file is a result of a model which excludes Race, Sex and Age field and predicts if loan has been approved or declined just 
    based in risk factors.
    
> Archives Folder
  
  1. Archives folder contains another instance of Juputer Notebook file where the model is designed in order to predict if the loan is denied or not denied 
     (vs.approved approved or not approved). Here 1 = Denied and 0 = Approved.
     
  2. This folder is just for additional reference and can be ignored.
