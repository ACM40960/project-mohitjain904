
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


<p align="justify">
The objective of this section is to study delves into the multifaceted realm of climate change, employing a systematic approach that involves four key dimensions: CO2 emissions, population dynamics, temperature fluctuations, and natural disaster occurrences. Here's how our analysis unfolded:
</p>

### Section 1: Carbon Symphony
   <p align="justify">
    Through a comprehensive study of global CO2 data spanning 1970 to 2021, a meticulous exploration unfolded. Initial plotting of the top 23 countries allowed for 
    the identification of the foremost five nations in both 1970 and 2021, culminating in a selection of six countries for further in-depth analysis. Among these, 
    the trajectory of China's emissions stood out starkly – from ranking fourth in 1970 to attaining the top spot in 2021. The United States maintained a steady 
    CO2 output, while India experienced a significant surge in emissions over the years. Russia's emissions remained relatively constant, while Japan displayed a 
    consistent emission level. Germany, on the other hand, showcased progress through emission reduction. With a correlation coefficient of 0.303, the null 
    hypothesis was rejected, affirming a substantial connection between Year and CO2 Emissions, underscoring the intricate relationship between temporal 
    progression and environmental impact.
    </p>

<p align="center">
  <img width="950" height="300" src="https://github.com/ACM40960/project-Rucha-Kardile/assets/133113442/57e98051-638a-4253-8361-f2112e3f86a0">
</p>


### Section 2: Population Dynamics
   <p align="justify">
   China and India: A Shared Affection for the Top Spot.
   <p>
   <p align="center">
   <img width="950" height="300" src="https://github.com/ACM40960/project-Rucha-Kardile/assets/133113442/293a88d6-4470-4307-93dc-f35c2b20b9b7">
   </p>
   
   <p align="justify">
   Shifting Our Gaze: From Global Populace to a Select Six - China, India, United States, Russia, Germany, and Japan. In a symphony of data, we harmonized 
   population insights to craft an intricate connection between societal dynamics and CO2 emissions within this elite group. As our investigation unfolded, a 
   profound melody emerged – an unmistakable chord binding population shifts and CO2 outputs. Like a well-composed sonata, our findings crescendoed to a resounding 
   conclusion: when the population swells, the orchestration of CO2 emissions rises in concert, an empirical testament to the rhythm of our changing world.
   </p>

   <p align="center">
   <img width="950" height="300" src="https://github.com/ACM40960/project-Rucha-Kardile/assets/133113442/5082a28c-5e8f-4922-931b-185e5ac1e08e">
   </p>

### Section 3: Thermal Tapestry
 <p align="justify">
Temperature, a Crucible of Change in the Global Warming Tapestry, Takes Center Stage. With a keen eye on this pivotal element, we embarked on a journey into temperature's sway over the chosen six: China, India, United States, Russia, Germany, and Japan. As we fused temperature data into our intricate mosaic, a rich tableau emerged, illuminating the interplay between CO2 emissions and population dynamics against the backdrop of temperature fluctuations. The resulting portrait paints a vibrant narrative of how these variables entwine, revealing a story both intricate and essential in our collective understanding of the ever-evolving challenge that is global warming.
<p>

   <p align="center">
   <img width="950" height="500" src="https://github.com/ACM40960/project-Rucha-Kardile/assets/133113442/1861a8fb-73ef-479a-bd5f-50d503bbd065">
   </p>

### Section 4: Disaster Resonance
<p align="justify">
Unmasking the Yearly Showdown: Humans vs. Nature in Disasters. From 1970 to 2021, it's been a tech-powered saga – every year, manmade disasters taking the spotlight over natural ones, all around the world. We sure know how to make an impact!!
<p>

<p align="center">
   <img width="950" height="300" src="https://github.com/ACM40960/project-Rucha-Kardile/assets/133113442/05609811-6c8d-4239-b33f-37c384b0e2ff">
   </p>

<p align="justify">
Diving into the Data: A Snapshot of Our Six Powerhouse Players. We've narrowed our gaze to China, Germany, India, Japan, Russia, and the United States. Here's what we uncovered:
<p>

<p align="center">
   <img width="800" height="250" src="https://github.com/ACM40960/project-Rucha-Kardile/assets/133113442/cd579612-5310-4455-a423-281d50a0a35c">
   </p>

A correlation of 0.857 between CO2 emissions and total deaths raises intriguing questions. These numbers, like threads, weave a narrative of our intricate relationship with our world and hint at the tales yet to be told.

<p align="justify">
But Here's the Twist: Unearthing an Engaging Anomaly. As our gaze shifted to the count of natural and technological disasters within our chosen six countries, a fascinating revelation emerged. Buckle up – in this surprising twist, three out of these six nations claim the highest tally for natural disasters. Who would've thought?
<p>

<p align="center">
   <img width="1000" height="700" src="https://github.com/ACM40960/project-Rucha-Kardile/assets/133113442/3437d4d4-c438-43ba-bd3e-6c7fd0d76e24">
   </p>

<p align="justify">
Unlocking Hidden Treasures 
A Country-by-Country Expedition. As we delved deep into the tapestry of each nation, an intriguing world unfolded before us:
In the United States, it's the Convective Storm that takes the natural disaster crown, reigning with the highest count. Across the Pacific, Japan dances to a different rhythm, boasting the highest tally in the realm of Tropical Cyclones.
Germany, snugly nestled in Europe, steps up with Convective Storms reigning supreme in its disaster portfolio. Meanwhile, far East in China, it's the realm of Technological Disasters where they lead, particularly in the explosion type.
Turning our sights to India, it's the roads that become the stage for the highest disaster count, as Road Subtypes take the spotlight. And on the vast expanse of Russia's landscapes, the skies become the canvas for the highest count, where Air Disasters paint their own story.

Each country is a unique tale in this global symphony of disasters, unfolding chapters of challenges and resilience in their own distinctive way.
<p>

Venturing Beyond Our Horizon: Seeking Validation in Research Articles. While our own findings lay the intriguing groundwork, let's journey to the code and seek validation from related research articles, ensuring a sturdy foundation for our claims
