# Predicting Life Ladder from UN Data

## Overview
This project analyzes the **World Happiness Report (WHR)**, an annual publication by the United Nations Sustainable Development Solutions Network (SDSN). The WHR explains the happiness and well-being of various countries worldwide. Data is collected via the Gallup World Poll, which measures well-being and happiness using a standardized set of survey questions.

The dataset used in this project contains data from **2008 - 2023**, with **11 variables** and **2199 observations** in its raw, uncleaned form. The main variable of interest is the **Life Ladder**, the national average response to the poll of life evaluations on
many aspects of quality of life. The dataset offers a unique opportunity to explore global happiness trends, with additional data on key qualityof life metrics such as GDP, freedom of decision, social support, generosity, corruption, and life expectancy among others.


## Goal
The primary objective of this project is to determine the most effective subset of predictors that best determine the quality of life, or **Life Ladder** across the globe.

## Data 

| Variable        | Description |
|-----------------|-------------|
|**Country Name** | **Name of country**  |
|**Year** | **Year of the observation**  |
|**Life Ladder** | **Measure of subjective well being**  |
|**Log GDP per capita** | **Logarithm of country's GDP per capita**  |
|**Social Support** | **Perceived social support; someone to count on?National average of binary responses (0,1)**  |
|**Healthy Life Expectancy at Birth** | **Average lifespan of healthy individual**  |
|**Freedom to Make Life Choices** | **Satisfaction of freedom to make life decisions**  |
|**Generosity** | **Residual of regressing national average answer to the question: “Have you donated money to a charity in the past month?”**  |
|**Perceptions of Corruption** | **Average of binary responses to the following: “Is corruption widespread throughout the government or not?” “Is corruption widespread within businesses or not?”**  |
|**Positive Affect** | **These measures include responses to the following questions: "Did you smile or laugh a lot yesterday?", "Did you experience enjoyment during a lot of the day yesterday?", and "Did you learn or do somethinginteresting yesterday?**  |
|**Negative Affect** | **Average of three negative affect measures in GWP. Worry, sadness, anger for question “Did you experience the following  feelings during A LOT OF THE DAY yesterday?"**  |

