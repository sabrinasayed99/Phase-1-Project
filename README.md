<img width="788" alt="Screenshot 2024-09-12 at 1 52 46 PM" src="https://github.com/user-attachments/assets/ae6099d0-08d8-404b-9400-f456032cc4ff">

## S.J. Corporation Fleet Addition

#### Author: [Sabrina Sayed](https://github.com/sabrinasayed99), [Jessie Freeelander](https://github.com/Anicca18)


## Overview:

The project has utilized a dataset of about 88,000 aviation accident events to assess the most cost efficient and safe aircrafts for investment. To gauge safety, a risk index was designed, weighing minor injury rates, major injury rates, and fatility rates in the event of an accident with substantial damage. Risk assessment of an aircraft make and model will directly influence investment recommendations, which will undergo futher assessment based on aircraft performance in visually impaired weather conditions, engine types, and number of engines.

## Business Problem:

S.J. Corporation is seeking to invest in private aircrafts to serve executive and business purposes. The company is looking to optimize output and efficiency by adding private aircrafts to the balance sheets. The best investment will provide C-Suite executives with efficiency, comfort, and safety.


## Data:

The data was sourced directly from the National Transportation Safety Board including aviation accident data from 1962 to 2023 covering civil aviation accidents and selected incidents in the United States and international waters.


## Results:

The Risk index was classified into 3 buckets: "High Risk", "Medium Risk", and "Low Risk". A strong postive correlation between average fatalites and Risk values, validates our risk index as our main safety metric.

<img width="847" alt="Screenshot 2024-09-12 at 5 14 27 PM" src="https://github.com/user-attachments/assets/de86cfde-51b2-4f0c-97ab-14f9df6cea37">


Utilizing a heat map, we are able to narrow our findings to the makes and models of aircrafts that meet our standards and business needs. The green boxes highlight the safest aircrafts based on our risk index, from which we will choose our top 3 recommendations to present to the board to put to a final vote.


<img width="572" alt="Screenshot 2024-09-12 at 4 22 51 PM" src="https://github.com/user-attachments/assets/49eedf3d-7bcb-4143-8852-75b8c9a14cab">



## Conclusions

Our final analysis has allowed us to make 3 recommendations of unique make-models for investment. These recommendations come from the list of low-risk aircraft that have an average risk value of less than 0.05, two engines, and a track record of more than a 0.6 average uninjured rate.

    Cessna 206: 
                Risk index < .05
                Unijured Rate > .60
                Two Engines
    Cessna 208: 
                Risk index < .05
                Unijured Rate > .60
                Two Engines
    Piper Pa-32: 
                Risk index < .05
                Unijured Rate > .60
                Two Engines




## Directory
[Presentation](https://docs.google.com/presentation/d/1Ozf2IYApusxuSufWZ89BW7ldopqlxSKTxPelf5tStxQ/edit?usp=sharing)

[Data Set](https://www.kaggle.com/datasets/khsamaha/aviation-accident-database-synopses)

## Repo Files
### Cleaned Data Only Folder
Cleaned Data Only contains our cleaned data frame anlysis called "Clean_Data_Finalized.ipynb".
### Data
Contains our raw data sets, and alternative dataframes that were built from the root set.
### Exploratory Data Analysis
Includes exploration of data sets and graphical representations of insights. The final version is called "Final Aviation EDA.ipynb".
### Images
Stores our images of all the graphs we created.
### Aviation.pdf
A pdf version of our presentation slides.



    
    
  
