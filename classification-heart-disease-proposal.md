#### Classification | Project Proposal

# Predicting Heart Attacks 

https://www.mayoclinic.org/diseases-conditions/heart-attack/symptoms-causes/syc-20373106


## Question
* What is the question behind your analysis or model and what practical impact will your work have?
    * Question ...
* Who is your client and how will that client benefits from exploring this question or building this model/system?
    * Client ...  
    * Benefits ... 

## Data Description
* What dataset(s) do you plan to use, and how will you obtain the data? 
    * Centers for Disease Control and Prevention, [Behavioral Risk Factor Surveillance System (BRFSS)](https://www.cdc.gov/brfss/index.html), [Personal Key Indicators of Heart Disease (Kaggle)](https://www.kaggle.com/datasets/kamilpytlak/personal-key-indicators-of-heart-disease)
* What is an individual sample/unit of analysis in this project?
    * One row is one respondent's answers to the BRFSS questions about and their demographics and medical history (n=319,795).  
* What characteristics/features do you expect to work with?
    * Demographics:
        - `Age Category`
        - `Race`
        - `Sex`
    * Health behaviors:
        - `Smoking`
        - `Alcohol Drinking`
        - `Sleep Time` 
        - `Physical Activity`
    * Health:
        - `Body Mass Index (BMI)`
        - `Difficulty Walking`
        - `General Health`
        - `Mental Health`
        - `Physical Health`
    * Chronic disease:
        - `Asthma`
        - `Diabetic`
        - `Kidney Disease`
        - `Skin Cancer` 
        - `Stroke`
* If modeling, what will you predict as your target?
    * The probability (high, medium, low) that a person will have a heart attack. 
    
## Tools
* How do you intend to meet the tools requirement of the project?
    * Python, numpy, pandas, sklearn
    * Matplotlib, Seaborn
* Are you planning in advance to need or use additional tools beyond those required?
    * None at this time.

## MVP Goal
* What would a minimum viable product (MVP) look like for this project?
    * Baseline classification model 
    * Two visualizations of feature interactions