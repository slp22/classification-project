#### Classification | Project Proposal

# Predicting Heart Disease   

## Question
* What is the question behind your analysis or model and what practical impact will your work have?
    * Could a model predict the probability of a patient having [heart disease](https://medlineplus.gov/hearthealthtests.html) based on the [risk factors](https://www.cdc.gov/HeartDisease/risk_factors.htm) in electronic health records?  
* Who is your client and how will that client benefits from exploring this question or building this model/system?
    * [Kaiser Permanente](https://healthy.kaiserpermanente.org/front-door), a [health maintenance organization (HMO)](https://www.investopedia.com/terms/h/hmo.asp) and integrated managed care consortium. Their business model is such that the organization is both the insurer and healthcare provider. 
    * Heart disease (which can lead to heart attacks) is the [leading cause](https://www.cdc.gov/heartdisease/facts.htm) of death in the U.S. for men and women. Kaiser would benefit from a model predicting patients' probability of a heart attack by focusing on patient with high risk before an attack, ensuring better health for patients and lower costs for the organization. 

## Data Description
* What dataset(s) do you plan to use, and how will you obtain the data? 
    * [Personal Key Indicators of Heart Disease](https://www.kaggle.com/datasets/kamilpytlak/personal-key-indicators-of-heart-disease) 
        * Subset of the [Behavioral Risk Factor Surveillance System (BRFSS)](https://www.cdc.gov/brfss/index.html)
        * Annual survey by the [Centers for Disease Control and Prevention](https://www.cdc.gov/)
    * [2020 BRFFS Codebook](https://www.cdc.gov/brfss/annual_data/2020/pdf/codebook20_llcp-v2-508.pdf)
* What is an individual sample/unit of analysis in this project?
    * One row is one respondent's answers to the BRFSS questions about and their demographics and medical history (n=319,795).  
* What characteristics/features do you expect to work with?
    * Demographics:
        - `Age Category`
        - `Race`
        - `Sex`
    * Health behaviors:
        - `Alcohol Drinking`
        - `Physical Activity`
        - `Sleep Time` 
        - `Smoking`
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