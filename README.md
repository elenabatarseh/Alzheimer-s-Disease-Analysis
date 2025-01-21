# Alzheimer's Disease Analysis

## Research Questions:
What is the relationship between cognitive and functional assessments on the diagnosis of Alzheimer’s?  
Are any assessments more likely to increase the chances of developing Alzheimer’s?

## Data Source
The Alzheimer’s Disease Dataset is collected from 2,149 patients. The dataset includes many variables from different categories such as demographics, lifestyle factors, medical history, clinical measurements, cognitive and functional assessments, symptoms, and a diagnosis of Alzheimer's Disease. Alzheimer’s disease is the most common form of dementia and is characterized by progressive memory loss and cognitive decline.  

## Variables
MMSE (Mini-Mental State Examination) Score: questionnaire used to measure cognitive impairment (scored 0-30)  
Functional Assessment Score: measures an individual’s level of function and ability to perform specific tasks (scored 0-10)  
ADL (Activities of Daily Living) Score: measures an individual’s ability to perform daily self-care activities, such as bathing, eating, getting dressed, etc.(scored 0-10)  
Behavioral Problems: 0 if no, 1 if yes  
Memory Complaints: 0 if no, 1 if yes  

## Exploratory Data Analysis
### Difference in mean MMSE between diagnosis groups
Using bootstrapping confidence interval: (3.555667, 4.958793)  
Because 0 is not included in this interval, we have sufficient evidence to conclude that mean MMSE score is significantly lower for those with Alzheimer’s than for those without Alzheimer’s. 

### Difference in mean functional assessment score between diagnosis groups
Using bootstrapping confidence interval: (1.976185, 2.455988)  
Because 0 is not included in this interval, we have sufficient evidence to conclude that the mean functional assessment score is significantly lower for those with Alzheimer’s than for those without Alzheimer’s. 

### Difference in mean Adl score between diagnosis groups
Using bootstrapping confidence interval: (1.816866, 2.294555)  
Because 0 is not included in this interval, we have sufficient evidence to conclude that mean ADL score is significantly lower for those with Alzheimer’s than for those without Alzheimer’s.

### Difference in proportion of memory complaints between diagnosis groups
Using bootstrapping confidence interval: (-0.2962983, -0.2246659)  
Because 0 is not included in this interval, we have sufficient evidence to conclude that the proportion of memory complaints is significantly higher for those with Alzheimer’s than for those without Alzheimer’s.

### Difference in proportion of Behavioral Problems between diagnosis groups
Using bootstrapping confidence interval: (-0.2084141, -0.1375122)  


