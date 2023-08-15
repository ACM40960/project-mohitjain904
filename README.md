
![](https://github.com/ACM40960/project-mohitjain904/blob/main/Images/Header.gif)

 <p align="justify">
   
# Earth Fever : The Unignorable impact of Climate Change

## Introduction

In the midst of the complex interplay between global climate change and its consequential impacts, this project embarks on a rigorous analysis of Antarctic mass and air temperature data. By meticulously examining the historical trends and fluctuations in these critical variables, we aim to uncover the nuanced relationship between the Antarctic mass balance and air temperature variations. This analysis spans geographical boundaries, encompassing five distinct countries, and seeks to illuminate the far-reaching implications of these interactions on both regional and global scales. Through this endeavor, we aspire to deepen our understanding of the intricate dynamics at play and contribute insights essential for informed climate policy formulation and adaptive strategies.

## Authors

- [@Mohit Padam Chand](https://github.com/mohitjain904)

- [@Rucha Ketan Kardile](https://github.com/Rucha-Kardile)
  
## Installation

</p>

Installing the Libraries

```bash
pip install seaborn
pip install pandas
pip install numpy
pip install plotly
pip install matplotlib
pip install statsmodels
pip install sklearn
pip install scipy
```

## Part 1 : Antarctica

### Objective :

<p align="justify">
In this comprehensive study, our primary focus is to examine the intricate relationships between various radiations - UV, Solar, Infrared, and N20 radiation - and air temperature. Through rigorous analysis, we seek to discern the extent of their influence on air temperature fluctuations. Subsequently, we endeavor to construct a predictive model utilizing the combined values of all four radiation factors to forecast air temperature accurately. Additionally, we aim to assess the predictive capacity of individual radiation components on air temperature, providing invaluable insights into their respective impacts.

In the second segment of our investigation, we delve into a comparative exploration between Antarctic mass and air temperature. Employing advanced plotting techniques, we aspire to unearth potential patterns and correlations between these two critical parameters. This endeavor holds the potential to unravel connections that could offer crucial insights into the dynamic interplay between Antarctic mass and temperature variations.

Transitioning to the third facet of our study, we shift our attention to a comparative analysis encompassing Gentoo penguin nests, air temperature, and ice mass. By examining these intricate relationships, we seek to decipher the complex interactions between environmental factors and the wellbeing of Gentoo penguin populations. This multifaceted analysis not only sheds light on the potential influences of temperature and ice mass on nesting sites but also offers a holistic perspective on the broader ecological implications.

Collectively, these three interlinked objectives form a comprehensive research endeavor that contributes to our understanding of the intricate web of interactions within Antarctica's ecosystem. Through empirical analysis, predictive modeling, and advanced visualization techniques, we aim to enrich the knowledge base surrounding climate dynamics, species habitats, and environmental shifts in this vulnerable yet crucial region. The insights garnered from this study hold the potential to inform policy decisions, conservation efforts, and proactive strategies in the face of a rapidly changing climate.
</p>

### Section 1 : Study Between Radiations and Air Temperature

We first perform statistical plotting using plotting techniques such as scatter plot , line plot etc to understand basic understanding of relationship between the variables like UV , Solar , Infrared Radiation , N2O and Air Temperature. 

<p align="center">
  <img width="460" height="300" src="https://github.com/ACM40960/project-mohitjain904/assets/82156509/6b51eb4a-fd9d-4b0c-93f3-b3bf5318dc3e">
</p>

<p align="center">
  <img width="460" height="300" src="https://github.com/ACM40960/project-mohitjain904/assets/82156509/5683ce21-ad18-420f-a63d-b2899009fe4e">
</p>

From these we clearly see that radiations have some relationship but to establish a clear picture we plot a heat map

<p align="center">
  <img width="460" height="300" src="https://github.com/ACM40960/project-mohitjain904/assets/82156509/b305805b-9101-49ff-a734-6e92f7d919ed">
</p>

From the above heat map , we can comprehend that UV , Solar , Infrared Radiations have the highest correlation with air temperature and N2O being the least.

We now plot a simple scatter plot to observe pattern of all radiations with air temperature

<p align="center">
  <img width="460" height="300" src="https://github.com/ACM40960/project-mohitjain904/assets/82156509/43330d81-f11e-45e7-ab2a-e36a0ed67fe8">
</p>

We observe that as radiations increase, the air temperature also increases 

We now develop a model which takes these radiations as Input and give future radiations.


## Part 2 : Metropolitian Cities
