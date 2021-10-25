## Team Cyber Crop-Bots

ISTA 429 Midterm project for MCLAS2021


**This is a project designed for MLCAS2021 Crop Yield Prediction Challenge.**


*In this competition, you will utilize a dataset consisting of 103,365 performance records over 13 years and 150 locations with weekly weather data for each location throughout the growing season of 30 weeks. In particular, you will develop machine learning algorithms that can accurately predict yearly crop yield for a particular performance record. Given the significance of the problem, we believe that our dataset provides an important scientific challenge with widespread applications in plant breeding, crop science research, and agricultural production.*


**Team Members:**

 - Sebastian Calleja. 
 - Hayden Payne. 
 - Melanie Hannah Grudinsch. 
 - Nik A Pearce. 
 - Abhishek Agarwal. 


**Familiarizing with our code repository**

Before we get started, you must have a updated your python to the newest release. 
Download or clone our repository from the given link in the readme. 

We have a single main branch in our repository, which holds the following files.
```
|- Dir Data
|- Dir Notebooks
|- LICENSE
|- LSTM_model_final.py
|- README.md
|- data_prep.py
|- lstm_traits_prep.py
|- lstm_weather_prep.py
```
Let us explotre our Data directory which contains the following files:
```
|- Data 
   |--Dataset_Competition.zip
   |--Description.txt
   |--MergedDataMidterm.csv
   |--avg_performance_record.csv
   |--trait_df.csv
   |--weather_short.csv
```

  + Dataset_Competition.zip contains the actual files from the competition. 

  + MergedDataMidterm.csv is a merged files combing the all the dataset in our code.

Moving to our Notebooks directory
```
|- Notebooks
   |--Data_Variable_Exploration.ipynb
   |--Description.txt
   |--Final_data_prep.ipynb
   |--Testing_Model.ipynb
```
  + Data_Variable_Exploration.ipynb is a Jupyter notebboks which has all the prep works and data set exploraytion for our project. Here we closely look at all the initail npy.
  + Testing_Model.ipynb is a notebooks where we test our differnt models. 
  
License : MIT License

```
|- LSTM_model_final.py
```
Our final file to run the project with the display of all the required result.

For our report: https://docs.google.com/document/d/1MCLDuSoEgxVEk9BChzzN8zxuc2Mf6TtiNUkkKQ56_IQ/edit?usp=sharing

