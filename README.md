# DISASTER RISK MANAGEMENT

# Introduction
Machine learning in disaster management holds a great potential to use predictive analytics to help alerting about upcoming calamities.
The aim of this project is to order, structure, preprocess ,analyze , and try to feed the data to a Machine Learning model in order to find statistics and meaningful numbers that can help us predict the what, when and where of the occurrence of the upcoming Catastrophes.

We worked on this project with the government of Valle del Cauca especially with the National Unit for disaster risk management who is participating in a data science convocation for the Secretary of Information and Communications Technology.
# Data
The data is presented as 22 Excel files. Each of them represents a specific year (1998 →2019). Every file has a different structure for the data (they don’t have the same columns, some of them have more columns than

Some data had different structures, some columns were missing in some files and others had additional information that is not to be found in other files. So the first thing we did was find the shared columns in every file and make a unified structure. Each one of us created a structure for his correspondent files and these structures were created. Which with the same technique, lead us to Final structure presented below:

![](https://github.com/Viiic98/disaster-risk-management/blob/main/images/finalStructure_I.png)
![](https://github.com/Viiic98/disaster-risk-management/blob/main/images/finalStructure_II.png)
![](https://github.com/Viiic98/disaster-risk-management/blob/main/images/finalStructure_III.png)

Once we had the final structure for all the 22 files we started with the cleaning process using SageMaker.

# Data cleaning and storage
We did the data cleaning process using AWS SageMaker service, also Python with Pandas and SQL. And for storage AWS S3
![](https://github.com/Viiic98/disaster-risk-management/blob/main/images/sagescreenshoot.png)
![](https://github.com/Viiic98/disaster-risk-management/blob/main/images/describe.png)

# Machine Learning Model
We use the SVM algorithm to build the model
## Advantages of Support Vector Machine Algorithm
* Accuracy
* Works very well with limited datasets
* Kernel SVM contains a non-linear transformation function to convert the complicated non-linearly separable data into linearly separable data.
## Disadvantages of Support Vector Machine Algorithm
* Does not work well with larger datasets
* Sometimes, training time with SVMs can be high

# What’s the next steps of the project?
* Create a Machine Learning model that can predict the future disaster events.
* Compare the model with others.
* Develop a deployable application.

All the process are well document on the [notebook](https://github.com/Viiic98/disaster-risk-management/blob/main/disaster_risk.ipynb) of this project

## Authors
Amine Neifer - [Github](https://github.com/AmineNeifer) / [LinkedIn](https://twitter.com/AmineNeifer/)<br>
Victor Arteaega - [Github](https://github.com/Viiic98) / [LinkedIn](https://www.linkedin.com/in/viiic98/)<br>
Pablo Andres Urbano De la Cruz - [Github](https://github.com/paurbano) / [LinkedIn](https://www.linkedin.com/in/pablourbanodelacruz/)<br>
