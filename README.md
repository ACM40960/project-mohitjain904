
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
  <img width="500" height="300" src="https://github.com/ACM40960/project-mohitjain904/assets/82156509/6b51eb4a-fd9d-4b0c-93f3-b3bf5318dc3e">
</p>

<p align="center">
  <img width="500" height="300" src="https://github.com/ACM40960/project-mohitjain904/assets/82156509/5683ce21-ad18-420f-a63d-b2899009fe4e">
</p>

From these we clearly see that radiations have some relationship but to establish a clear picture we plot a heat map

<p align="center">
  <img width="600" height="600" src="https://github.com/ACM40960/project-mohitjain904/assets/82156509/b305805b-9101-49ff-a734-6e92f7d919ed">
</p>

From the above heat map , we can comprehend that UV , Solar , Infrared Radiations have the highest correlation with air temperature and N2O being the least.

We now plot a simple scatter plot to observe pattern of all radiations with air temperature

<p align="center">
  <img width="900" height="300" src="https://github.com/ACM40960/project-mohitjain904/assets/82156509/43330d81-f11e-45e7-ab2a-e36a0ed67fe8">
</p>

<p align="justify">
We observe that as radiations increase, the air temperature also increases and vice versa.

Our comprehensive analysis of the interplay between UV Radiation, Solar Radiation, Infrared Radiation, air temperature, and the concerning trend of increasing N20 levels paints a vivid portrait of the intricate dynamics shaping our climate system. Notably, we unearthed a compelling correlation between these radiation types and air temperature. Specifically, Infrared Radiation exhibited an astonishingly high correlation coefficient of 0.99 with air temperature, followed closely by UV Radiation. This suggests a strong association between radiative energy influx and atmospheric heating.

Furthermore, our observations revealed a synchronized pattern: as radiation levels rise, so does the ambient air temperature, and conversely, decreases in radiation are mirrored by drops in temperature. This synchronous relationship underscores the significant role radiation plays as a driver of temperature variations. The linkage between radiation and temperature is a pivotal aspect in comprehending the complexities of climate change, highlighting the need for continuous monitoring and assessment.

Intriguingly, our analysis brought to light a disconcerting trend regarding N20 levels. The exponential year-on-year increase in N20 levels raises alarms, pointing towards a potentially significant contributor to the greenhouse effect. N20, a potent greenhouse gas, can have far-reaching consequences for global climate stability. This observation highlights the urgency of addressing this trend through comprehensive measures aimed at mitigating its exponential growth, thereby curbing its impact on our fragile climate balance.

These findings collectively emphasize the intricate web of interactions that govern our planet's climate system. The strong correlations between radiation types and air temperature accentuate the influence of radiative energy on temperature dynamics. Simultaneously, the escalating N20 levels underscore the complex nature of greenhouse gas emissions and their implications for climate change. This analysis serves as a clarion call for heightened environmental awareness and responsible action to address the challenges posed by these interconnected factors.

In conclusion, our analysis sheds light on the intimate relationship between radiation, temperature, and the worrisome surge in N20 levels. As we grapple with the complexities of climate change, the insights garnered from this study offer crucial guidance for crafting informed policies and strategies to safeguard our planet's delicate ecological equilibrium. By leveraging these insights, we can foster a sustainable future that prioritizes responsible stewardship of our environment.

</p>

### Section 2 : Antarctic Ice mass and Air Temperature : 

We first perform statistical plotting using plotting techniques such as scatter plot , line plot etc to understand basic understanding of relationship between the variable Antarctic Ice Mass and Air Temperature. 

<p align="center">
  <img width="900" height="300" src="https://github.com/ACM40960/project-mohitjain904/assets/82156509/ef2415d5-dca9-4f34-b60f-d346b9982b0b">
</p>

<p align="center">
  <img width="900" height="300" src="https://github.com/ACM40960/project-mohitjain904/assets/82156509/6fdd4edc-895f-4846-9899-544952555c5c">
</p>

<p align="center">
  <img width="900" height="300" src="https://github.com/ACM40960/project-mohitjain904/assets/82156509/5b6fd37b-e4a0-45e2-be6b-a031acd61603">
</p>

<p align="justify">
Our meticulous analysis of the relationship between ice mass and air temperature in Antarctica reveals a stark and concerning trend. Over successive years, we observed a clear and inverse correlation: as the average annual temperature experiences an upward trajectory, the average ice mass demonstrates a corresponding and consistent decline. This observation highlights the fragility of the Antarctic environment in the face of rising temperatures.

The implications of this correlation are profound. The decreasing ice mass signifies the impact of warming temperatures on the stability of Antarctica's ice sheets. As ice mass diminishes, the potential for sea-level rise becomes increasingly tangible, with far-reaching consequences for global coastlines and ecosystems.

These findings align with broader climate change concerns and underscore the urgency of addressing anthropogenic factors that drive temperature increases. They also serve as a stark reminder of the pressing need for international cooperation to mitigate greenhouse gas emissions and curb further environmental degradation. Our analysis emphasizes the critical role of scientific research in informing policy decisions and calls for immediate action to safeguard Antarctica's ice mass, the delicate ecosystems it supports, and the global environment as a whole.

</p>

### Section 3 : Gentoo Penguins

<p align="justify">
Understanding how gentoo penguins respond to variations in ice mass and air temperature is of paramount importance in the context of climate change. As the Earth's climate warms, polar regions experience heightened environmental shifts, impacting various species that rely on the delicate balance between ice, temperature, and ecosystem health. By analyzing the correlation between penguin nest numbers and these environmental factors, we can discern how gentoo penguins adapt to these changes, offering a glimpse into their resilience and ability to survive in the face of adversity. This analysis not only sheds light on the intricate relationship between these creatures and their environment but also underscores the broader implications of climate change for fragile ecosystems and the urgent need for conservation efforts to ensure the survival of not just gentoo penguins, but countless other species as well.
</p>
<p align="center">
  <img width="900" height="300" src="https://github.com/ACM40960/project-mohitjain904/assets/82156509/cfefdb23-410b-4d09-b68f-1b06731cd3df">
</p>

<p align="center">
  <img width="500" height="300" src="https://github.com/ACM40960/project-mohitjain904/assets/82156509/70aee2bf-6a56-451b-8939-c49d44a4e306">
</p>

<p align="center">
  <img width="500" height="300" src="https://github.com/ACM40960/project-mohitjain904/assets/82156509/803ab351-a763-439e-a120-9f2e412ebc6a">
</p>

<p align="justify">
 
Our analysis of the correlation between gentoo penguin nests and both ice mass and air temperature offers a fascinating glimpse into the adaptability of these remarkable creatures in the face of shifting climatic conditions. As air temperatures rise, we noted a corresponding increase in penguin nest numbers, indicating the species' capacity to adjust to warmer surroundings. Equally intriguing is the finding that diminishing ice mass coincides with a higher count of penguin nests. This suggests a significant behavioral response to climate-induced ice loss, showcasing the penguins' ability to adapt their nesting habits as their habitat transforms.

These observations collectively underscore the gentoo penguins' remarkable resilience and adaptability to the changing environment. The rise in air temperature and the reduction in ice mass are both emblematic of broader climate change trends affecting polar regions. The fact that penguins are altering their nesting patterns in response to these changes speaks volumes about their ability to navigate a rapidly evolving ecosystem.

However, while the adaptability of gentoo penguins is remarkable, it's crucial to interpret these findings within the broader context of climate change. The increasing air temperatures and decreasing ice mass are ultimately driven by anthropogenic factors, and these changes can have cascading effects on the delicate balance of polar ecosystems. The penguins' adaptive responses, while inspiring, also serve as a poignant reminder of the urgent need for global efforts to mitigate and address the root causes of climate change. The fate of these charismatic penguins serves as a microcosm of the broader challenges that our planet faces as it grapples with the consequences of a warming world.

</p>





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


## Conclusion :


<p align="justify">
The culmination of our analysis underscores a critical nexus between escalating radiation levels, temperature spikes, adaptive responses, and the looming specter of disasters in the context of global warming. Our findings accentuate a distressing trend: the relentless rise in radiation, including CO2, UV, Solar, and Infrared, is directly proportional to the surge in temperatures across the world. This resounding correlation underscores the pivotal role these radiations play in shaping our climate.

Crucially, while our analysis reveals a degree of adaptive resilience within human and other living populations, it is imperative to recognize that such adaptation should not be misconstrued as a warrant for complacency. The fact that societies can acclimatize to higher temperatures should not overshadow the urgency to mitigate these escalating radiation levels. Indeed, our study serves as a poignant reminder that the adaptive capacity of living organisms does not grant us license to disregard the potential long-term consequences of unchecked radiation proliferation.

Equally pivotal is the acknowledgment of the dual influence of disasters on exacerbating global warming. The disconcerting revelation that man-made disasters outstrip natural ones in their contribution to this crisis presents a sobering reality. These anthropogenic catastrophes, be they industrial accidents or environmental mismanagement, carry the power to magnify the deleterious effects of increasing temperatures and radiation levels.

In conclusion, our analysis paints a multi-faceted portrait of the global warming landscape. The escalation of radiation levels and the consequent temperature surges underscore the inextricable connection between human activity and environmental transformations. While our findings elucidate the resilience of living populations in the face of these changes, they simultaneously serve as a clarion call for concerted action. Urgent measures are imperative to curb the proliferation of radiation, both through prudent policies and individual behavioral shifts. Moreover, the revelation of man-made disasters as pivotal drivers of global warming necessitates a profound reevaluation of our stewardship of the planet. The crossroads we face demand nothing short of a united commitment to reverse this trajectory and forge a sustainable path forward for the well-being of our planet and generations to come.
</p>

## Future Work : 

<p align="justify">

Based on our extensive analysis, a compelling avenue for future work is to delve into the interconnectedness of increasing radiation and temperature variations, considering the cumulative impact of CO2, UV, Solar, and Infrared radiation. Investigating the specific mechanisms through which these radiations drive temperature changes could yield crucial insights for targeted climate mitigation strategies.

Simultaneously, further research should probe the adaptive capacity of diverse living populations in the face of escalating temperatures, with a focus on long-term implications and potential thresholds. Employing advanced modeling techniques, the predictive behavior of both wildlife and human communities could be projected under various climate scenarios, aiding proactive adaptation planning.

Moreover, given the role of disasters in exacerbating global warming, comprehensive analysis of man-made disasters' ecological and climate ramifications is essential. By quantifying their contributions to radiative changes and temperature fluctuations, we can highlight the urgency of disaster prevention and management measures.

Synthesizing the results from radiation, temperature, and disaster analyses, interdisciplinary research could unravel intricate feedback loops and potentially identify synergistic interventions to mitigate environmental degradation. Ultimately, this multifaceted approach holds the promise of fostering a more resilient and sustainable global ecosystem in the face of ongoing climate challenges.

</p>

## Code : 

- [@Antarctic Data Study](https://github.com/mohitjain904)

- [@Metropolitian Study](https://github.com/Rucha-Kardile)

## Dataset Reference : 

The Datasets used throughout the study have been referenced in the respective python files.

## Acknowledgement

I would like to express my sincere gratitude to Dr. Sarp Akcay for all his guidance and support throughout the module at University College Dublin. I am grateful to the University College Dublin for providing resources that made this project possible. Lastly, I want to thank everyone who directly or indirectly supported me during this endeavor.
