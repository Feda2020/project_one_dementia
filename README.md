# Dementia Risk Analysis

## Overview
This repository contains an analysis of factors related to dementia, cognitive test scores, and their associations with various lifestyle and medical features, including physical activity, smoking status, alcohol consumption, and depression status. The goal of the project is to investigate potential correlations and insights that could help in understanding the risk factors of dementia and how they affect cognitive performance.

## Dataset
The dataset used in this analysis includes features such as:

- **Medical conditions** (e.g., Diabetic, Heart Disease, Hypertension)
- **Lifestyle factors** (e.g., Physical Activity, Smoking Status, Alcohol Consumption, Nutrition Diet)
- **Cognitive and mental health indicators** (e.g., Depression Status, Cognitive Test Scores)
- **Genetic factors** (e.g., APOE ε4 status)
- **Demographic data** (e.g., Age, Gender, Education Level)

### Key Columns:
- **Dementia**: Binary indicator (1 or 0) for dementia status.
- **Cognitive_Test_Scores**: Scores from cognitive assessments, used to measure cognitive function.
- **Physical_Activity**: Level of physical activity, categorized as Sedentary, Mild, Moderate, etc.
- **Smoking_Status**: Smoking history categorized as Current Smoker, Former Smoker, or Never Smoked.
- **AlcoholLevel**: Continuous variable representing alcohol consumption levels.

## Analysis Goals
The analysis focused on answering two main questions:

1. How does alcohol consumption correlate with dementia when controlling for other variables like age and smoking status?
2. How do physical activity and smoking status impact cognitive test scores?

## Steps Involved
The project followed these steps:

1. **Data Exploration**: Initial exploration of the dataset, checking correlations, and identifying key features.
2. **Visualization**: Detailed visualizations to uncover patterns and trends related to dementia and cognitive function.
3. **Multivariate Analysis**: Examined the effects of multiple variables on dementia and cognitive test scores, controlling for confounding factors like age and smoking status.
4. **Interaction Analysis**: Explored how the interaction of physical activity with smoking status affects cognitive test scores.

## Results

### 1. Alcohol Consumption and Dementia:
- No strong correlation was found between alcohol consumption and dementia (𝑟 = −0.0037).
- Controlling for age and smoking status, alcohol consumption still did not show a significant relationship with dementia.
- Other factors like depression status and cognitive test scores were stronger predictors of dementia.

### 2. Physical Activity and Smoking on Cognitive Test Scores:
- **Physical Activity**: Higher physical activity levels, especially moderate activity, were associated with better cognitive test scores.
- **Smoking Status**: Never smokers consistently had higher cognitive test scores compared to current and former smokers.
- **Interaction**: Physical activity appeared to mitigate some negative effects of smoking on cognitive test scores, but sedentary smokers had the lowest cognitive performance.

## Visualizations
Key visualizations used in this analysis include:

- **Boxplots**: To compare cognitive test scores across different categories of physical activity and smoking status.
- **Scatterplots with Regression**: To show trends between alcohol consumption and dementia, controlling for age and smoking status.
- **Interaction Plots**: To highlight how physical activity and smoking status together impact cognitive performance.
