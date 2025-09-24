# Analysis of the quality and satisfaction of life of European young adults 
## Aim of the project
The analysis was made to categorize European countries based on selected economic and social measures that may influence or determine the level of quality of life in a given country, and to examine the factors influencing the level of life satisfaction. Original data is stored in the  `data/raw/`.
## Why I've chosen this topic
Many countries in the European Union have displayed significant economic growth in recent years, but this has not solved the existing problems that young adults face.
On top of that, high rental costs increase, lifestyle and mental diseases, and unemployment contribute to isolation and poor well-being. Global happiness reports, such as those published by the World Happiness Report, show that countries with higher GDP per capita tend to have higher levels of life satisfaction; however, the issue is much more complex.
Understanding what influences citizens' happiness can help governments and organizations create policies that improve society's overall well-being. For example, increasing access to public services and improving working conditions are shown to positively influence the quality of life.
## Questions related to the goal
In order to fulfill the goal of the analysis I created more specific questions:
* To what extent can the life satisfaction of people aged 25-34 be explained by variables determining well-being, health and access to care, as well as the economic conditions in the given country?
* Are life satisfaction and high fertility rates closely related?
* Do geographically and culturally related countries exhibit comparable levels of life satisfaction, health, and fertility?
## Data used in the project
Data was downloaded from Eurostat and included seven variables from 2022:
* GDP - GDP per capita
* MED - reported unmet needs for medical examinations because travel or the waiting list is too expensive or too far
* ILC HP - percentage of people who say they have not been happy at all in the last 4 weeks
* ILC_SAT - overall life satisfaction index
* FER - fertility rate
* EMPL - indicator of people not in employment or education
* HLTH - indicator of poor or very poor health
## Key results
* The chosen variables related to  well-being, health and access to care, as well as the economic conditions doesn't strongly correlate or explain the average life satisfaction of adults aged 25-34 in a country. 
* The classification yielded few clusters containing countries with similar characteristics. The most similar group included Bulgaria, Turkey, North Macedonia, and Montenegro, which stood out due to their citizens' low life satisfaction
## Methods used in the analysis
* Spearman and Pearson correlation 📑
* Linear Regression 📈
* Cluster Analysis 🪵
## Requirements to open the project locallly
* Python **3.9**
* JupyterLab/Jupyter Notebook
* Packages from requirements.txt

## Instalation and running 
 **Clone repo from GitHub**
   ```bash
   git clone git@github.com:kacper22g/EU_citizens_satisfaction.git
   cd EU_citizens_satisfaction 







