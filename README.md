# Student_Profiler 0.0

A decision tree based model which uses Personality Assesment, Emotional Quotient and Personal Data of students to predict perfomance. The predicted values can be used as pre-diagnostic markers for educationists to equip with them information which better enables them to give more personalised attention to students. 

## Data collected 

900 students were surveyed for this data collection exercise, their identies have been anonymised for privacy reasons.

### Feature Description 
The scaling factors are mentioned in the respective jupyter notebooks. Basic statistics of the features are given below.  


|                    | Family Size | Average Study Time | Motivation | Intuitive Index  | Self Awareness | Health | Parental Income | Tuition Count  |
|--------------------|-------------|--------------------|------------|------------------|----------------|--------|-----------------|----------------|
| Count              | 890         |                890 | 890        | 890              | 890            | 890    | 890             | 890            |
| Mean               | 0.52        | 0.45               | 0.63       | -0.08            | 0.385          | 0.453  | 0.513           | 0.228          |
| Standard Deviation | 0.18        | 0.11               | 0.12       | 0.23             | 0.12           | 0.19   | 0.288           | 0.092          |
 

 ### Background 
 The school is from a Tier 3 city in India. Socio-Economic barriers become more prominent in such places compared to metropolitan cities. However, schools still face the same kind of head count of over 2000 students making it next to impossible to give personalised attention to students. Our goal is to be able to identify and then eventually let the proper authorites provide help at the correct time to students. 
 
## Model 

Baseline results for different modeles. Models were run on Scikit Learn -0.20.0.1, Python - 3.6  

| Model  | MSE  | R2  |
|:-:|:-:|:-:|
| SVM  | 282.77  | -1.4  |
| Decision Tree  | 476.35  | -0.23  |
| Random Forest  | 282.21  | -1.23  |
| Linear Regression  | 276.41  | -1.3  |
| Neural Network  | 283.08  | -0.78  |
| KNN  | 317.31  | -3.57  |
 

 ## Authors 
 Abhor Gupta  
 
 
 Ashitabh Misra  
 
 Rohit Kar  
 
 
