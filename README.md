# An Investigation of Particulate Matter 2.5 in the DMV area during the COVID-19 Pandemic
#### Niko Darby, Snehika Pandey, Tamrat Workineh

## Abstract

##### COVID-19 (SARS-COV-2) is a respiratory virus that has the capability to cause pneumonic symptoms and death amongst patients. Thus far, in the United States of America there have been over 650K deaths during the SARS-COV-2 pandemic. Confounding factors such as pollutants can have an effect on the rate of illness amongst infectants. In this particular study, we will be examining the pollutant known as particulate matter 2.5 (PM2.5). Particulate Matter 2.5 (PM2.5) is a carcinogen that is known to cause epigenetic and genetic alterations that can lead to severe illness. Majority of the illnesses that derive from particulate matter 2.5 are respiratory and cardiovascular based. This is significant since COVID-19 also affects the respiratory and cardiovascular sectors of conspecifics.  Rather high concentrations of particulate matter 2.5 have been witnessed in several sectors of the United States of America. We examined the influx of particulate matter 2.5 in the Washington, DC area during the COVID-19 pandemic in comparison to alternative pollutants. Our hypothesis was supported that our predictive model of Particulate Matter 2.5 concentrations should decrease during the COVID-19 pandemic and that there will be an increase during the re-opening of the economy in late 2020 and 2021 onward. The PRPUI analyzer was also constructed as a front-end user-interface for analyzing different pollutants.

###### Note:
###### Capstone Project is the group project with team members from a diverse experience and bachground. We try to Investigation of Particulate Matter 2.5, 10 and gases() presence in the DMV area for the span of 5 years. Our Aim is to Investigate Particulate Matter and Gases concentrations in the DMV area during the COVID-19 pandemic and predict the trends over various spans of time preceeding during and post pandemic. The data will be procured from the United States Environmental Protection Agency (EPA)


## Introduction 

##### COVID-19 (Sars-COV-2) is a pneumonic-based respiratory virus that originated in Wuhan, China. COVID-19 has led to a pandemic with over six-hundred fifty thousand deaths in the United States of America and over four million deaths globally. This virus has been observed to have major effects on the respiratory and cardiovascular systems of infectants (Aveyard et al. 2021; Ebinger et al. 2020; Clerkin et al. 2020; Bansal, 2020 ). Symptoms of COVID-19 include tussis, fatigure, fibrous aches, pyrexia or chills, or more (Aveyard et al. 2021; Ebinger et al. 2020; Clerkin et al. 2020; Bansal, 2020 ). Individuals with pre-existing disorders such as obesity, cardiovascular disease, or respiratory disorders are considered at-risk as they are more prone to fatality via COVID-19 (Aveyard et al. 2021; Ebinger et al. 2020; Clerkin et al. 2020; Bansal, 2020 ).  With COVID-19 mutating and thus having multiple variant iterations, the virus will continue to become more potent and cause more deaths across the globe. Unfortunately, not only will the novel variants of COVID-19 lead to omnipotency, but confounding factors such as pollutant concentrations will as well. In this manuscript, we will focus primarily on the respiratory aspects of COVID-19 by observing trends of the common pollutant known as  Particulate Matter 2.5 and other confounding pollutants during the COVID-19 pandemic.

##### Particulate Matter 2.5 is a particle that is less than 2.5 micrometers large (Keet et al. 2017; Zhang et al. 2019; White et al. 2019; Tecer et al. 2008; Comunian et al. 2020; Shafinaz et al. 2021). Particulate Matter 2.5 commonly derives from automobiles, construction, and deforestation (Keet et al. 2017; Zhang et al. 2019; White et al. 2019; Tecer et al. 2008; Comunian et al. 2020; Shafinaz et al. 2021). This particular pollutant can cause major health disorders within conspecifics upon inhalation (Keet et al. 2017; Zhang et al. 2019; White et al. 2019; Tecer et al. 2008; Comunian et al. 2020; Shafinaz et al. 2021). Disorders that arise from particular matter 2.5 exposure includes lung cancer and other respiratory disorders (Keet et al. 2017; Zhang et al. 2019; White et al. 2019; Tecer et al. 2008; Comunian et al. 2020; Shafinaz et al. 2021). Particulate matter 2.5 has been observed to have major effects on conspecifics that have asthma and any alternative respiratory disorders (Keet et al. 2017; Zhang et al. 2019; White et al. 2019; Tecer et al. 2008; Comunian et al. 2020; Shafinaz et al. 2021). As a result of particulate matter 2.5 being a major contributing factor for respiratory disorders, it is essential to observe how particulate matter 2.5 can affect victims of COVID-19. When conspecifics are exposed to particulate matter 2.5, the transmission of COVID-19 increases significantly (Keet et al. 2017; Zhang et al. 2019; White et al. 2019; Tecer et al. 2008; Comunian et al. 2020; Shafinaz et al. 2021). Particulate matter 2.5 is a known contributor for the enhanced transmission of COVID-19 (Keet et al. 2017; Zhang et al. 2019; White et al. 2019; Tecer et al. 2008; Comunian et al. 2020; Shafinaz et al. 2021). In fact, it has been observed that particulate matter 2.5 particles contain COVID-19 viral fragments that can promote the spread of the virus (Keet et al. 2017; Zhang et al. 2019; White et al. 2019; Tecer et al. 2008; Comunian et al. 2020; Shafinaz et al. 2021). In essence, not only is particulate matter 2.5 known for promoting oncogenesis, but it can also promote the matriculation of COVID-19. Since particulate matter 2.5 is correlated with increased rates of COVID-19 infection, it is essential to examine the general concentration of PM2.5 during the COVID-19 pandemic and before. This will ultimately allow one to determine the correlations between other pollutants and additional confounding factors - such as COVID-19 mortalities. 

##### Resultantly, while observing the trends of COVID-19 throughout the 2019-2020 period, we hypothesize that in the Washington, District of Columbia, area, PM2.5 will show a decrease during the earlier periods of the COVID-19 pandemic. However, in the later periods of 2020, the PM2.5 concentrations will begin to increase due to elevated human activity. PM 2.5 concentrations will be observed in relation to alternative pollutants such as Nitrogen Dioxide, Carbon Monoxide, and Sulfur Dioxide within the Washington, D.C. area from the periods of 2015-2020 to procure an accurate depiction of how PM 2.5 altered during the pandemic. PM 2.5 concentrations will correlate with the air quality trends and trends of COVID-19 cases and deaths. 


## Methods

### Data
##### The data for this investigation was procured from multiple sources. The pollutant and GIS mapping data data for PM2.5, PM10, SO2, NO2, and CO was procured from the Environmental Protection Agency's (EPA) Open Air Quality dataset. Combined, the pollutant dataset comprised of over 30K data points. COVID-19 related data was procured from the Johns Hopkins University GitHub portal. The COVID-19 dataset consists of >800K data points. 

### Exploratory Data Analysis
##### The connection between major pollutants(PM2.5 and NO2) and the Air Quality Index, correlation between the species of pollutants and the relation to Covid-19 are the focus areas of the Exploratory Data Analysis. Our Aim is twofold, first to understand the relation between the species of pollutants and second is to understand the relation between the pollutants and the Covid-19. We collected Data from the EPA (To assess the relationship between air pollutant concentrations and COVID-19 fatality in District of Columbia state,we employ daily data at the city level)and We conducted a statistical analysis that confirms possible correlations among the number of daily cases and several factors related to the air quality(Andrea et al.)This work reports a correlation analysis, which is a statistical study that evaluates thestrength and the sign of a relationship between variables i.e between the species of pollutants, mean concentration of pollutants and Air Quality Index(AQI) between 2015 to 2020. On observing the data of PM2.5 we found the boxplot of the "Daily Mean Concentration" and "Daily AQI Value" as in the given figures. 
##### We also observed the PM2.5 concentration as per Lattitude and Longitude.
##### We combined the PM2.5 with the other gaseous pollutants and formed a Table, As mentioned in part I , Initially the dataset containing 879531 Columns and 29 Rows were Collected from Environmental Protection Agency (EPA). Based on the data science process, The large data set has many attributes some of which are irrelevant to data mining or some are redundant. The attribute subset selection reduces the volume of data by eliminating the redundant and irrelevant attribute and gives us the following Table


### Linear Regression
##### Machine learning with Scikit-learn was utilized to determine the correlation between Particulate Matter 2.5, other confounding pollutants (NO2, SO2, CO), Air Quality Index, and COVID-19 mortalities. As a result of multiple features being utilized in this analysis that are potentially correlated, the linear regression analysis will be conducted while taking multicolinearity into consideration. 

### Data Visualization

##### The Python package known as Matplotlib was utilized to construct figures during each analysis. Figures such as box charts, scatter plots, bar plots, and matrices were constructed to allow end-users the ability to visualize and comprehend the attained results. 


### Django Backend Development
HTML, CSS, and Javascript for the Front-End.


## Results 

### Washington, DC Compiled Pollutant Statistics
#### Figure 1: Pollutant Correlations with PM2.5
![](https://github.com/darbyna/DATA606_Capstone/blob/main/CPST.JPG?raw=true)


#### Figure 2: Average Pollutant Concentrations
![](https://github.com/darbyna/DATA606_Capstone/blob/main/CPCP.JPG?raw=true)


#### Figure 3: Pollutant Concentrations in Washington, DC
![](https://github.com/darbyna/DATA606_Capstone/blob/main/CPCPCP.JPG?raw=true)



#### Figure 4: Pollutant Concentrations and Relative Air Quality Indices
![](https://github.com/darbyna/DATA606_Capstone/blob/main/download%20(12).png?raw=true)



#### Figure 5: Matrix of PM2.5 in Relation to Air Quality Index
![](https://github.com/darbyna/DATA606_Capstone/blob/main/Heatmap.png?raw=true)



#### Figure 6: Ordinal Least Squares (OLS) Predictive Model of PM2.5 (2015-2021)
![](https://github.com/darbyna/DATA606_Capstone/blob/main/OLS.JPG?raw=true)



#### Figure 7: OLS Model Results
![](https://github.com/darbyna/DATA606_Capstone/blob/main/Screenshot%202021-10-27%20132116.png?raw=true)



#### Figure 8: Linear Regression Model of PM2.5 and COVID-19 Deaths
![](https://github.com/darbyna/DATA606_Capstone/blob/main/linmod.JPG?raw=true)

#### Figure 8 is a regression result depicting a corelation of PM2.5 and IncreaseDeath due to Covid Panedmic.

#### Figure 9: COVID-19 and Pollutants Intelligence Charts

![result-1](https://user-images.githubusercontent.com/90915655/137561550-6bc7c691-2779-440a-9ced-5a799a75ba53.jpg)   
![result-3](https://user-images.githubusercontent.com/90915655/137561571-b941c4fb-99fb-468a-a3e0-e5111c5d7995.jpg)  
![result-4](https://user-images.githubusercontent.com/90915655/137561582-65823ceb-5800-44c0-82f5-787bde562f55.jpg)
   
#### Figure 9 shows the relationship of  Polutant gases and  IncreaseDeath  due to Covid Panedmic. On the first out put refers to the realtionship of all features and 
    the target variable (Increase death). From the figure it can be observed that  both the features and the target are generally show similar trends.   
    on the second output shows specifically the relationship of PM2.5 and IncecreathDeath. Both shows positve relationship. The output 69 shows the relationship
    between Carbon     monoxide and Increasedeath. From the figure it can be seen that less effect of Carbon Monoxide againist the target. 
       
#### Figure 10: Matrix of Pollutants and COVID-19 Deaths
    
   #### The heat map depicting the relationship of the gaseous elements.From the graph, we can see that as one read from bottom to top -
   #### bold green , shows strong correlation .N02 and CO have srtong correlation with PM2.5 and Covid death.
   
![result-5](https://user-images.githubusercontent.com/90915655/137561586-0099f290-e62f-47bd-92f0-48d549634c86.jpg)



#### Figure 11: Preview of User Interface for Pollutant Analysis

![](https://github.com/darbyna/DATA606_Capstone/blob/main/PRPUIS.JPG?raw=true)

## Discussion and Conclusion

#### Discussion of the Research
The results indicate that the PM2.5 concentration will be high as a consequence of increased human activity post-quarantine. Studies have shown a correlation between the Air Quality Index, PM2.5, and confounding pollutants (Comunian et al., 2020). This Analysis supports the theory that the PM2.5 concentrations will be rather low during the earlier periods of the COVID-19 pandemic but increase during the later periods as human activity increases. The data suggests that the daily mean of PM2.5 concentration served an important role in discovering the relationship between COVID-19 fatalities and pollutants.

#### Interpretation
In line with the hypothesis, our predictive model showed that PM2.5 concentrations certainly increased upon elevated homosapien activity at the end of 2020. Contrary to the hypothesized association, causal relationship was not proved, the rise in COVID-19 deaths is related to the rise in the pollutants - specifically PM2.5. The result does not contradict with any of the studies as this is novel work and can lead to further research in the study of environment and disease.

#### Implication
These results are based on the existing evidence of PM2.5, PM10, NO2, CO, O3, and SO2 concentration (Keet et al. 2017; Zhang et al. 2019; White et al. 2019; Tecer et al. 2008; Comunian et al. 2020; Shafinaz et al. 2021). The experiment provides a new insight into the relationship between PM2.5 and NO2 (Keet et al. 2017; Zhang et al. 2019; White et al. 2019; Tecer et al. 2008; Comunian et al. 2020; Shafinaz et al. 2021). This result should be taken into account when considering how to measure the environmental factors which could lead to the rise in COVID-19 transmission within the DC area (Keet et al. 2017; Zhang et al. 2019; White et al. 2019; Tecer et al. 2008; Comunian et al. 2020; Shafinaz et al. 2021). The data contributes a concise understanding of PM2.5 concentration’s contribution towards COVID-19 fatalities (Keet et al. 2017; Zhang et al. 2019; White et al. 2019; Tecer et al. 2008; Comunian et al. 2020; Shafinaz et al. 2021).

#### Limitation
The generalizability of the result is limited by the geospatial features which were very limited and only focused on the site of the collection. The reliability of the data is impacted by the source of data generation, as it is unclear as to if the sample collection was based on site location, the county, or zip-code. Due to lack of geospatial features variability we were unable to construct a graph on the basis of county or more precise locations. The methodological choices were constrained by the number of limited features.

#### Recommendation 
Further research is needed to establish if there was any connection between the PM2.5 concentration and lung disease. Further studies should take account of how to select data in order to find the relation between PM2.5 concentration and the Lung diseases. Future studies will also investigate PM2.5, COVID-19 fatalities, and confounding pollutants in the Maryland and Virginia areas.



## Citations
* Convert to proper format when time allows - Before the end of the project *
 
1. Aveyard P, Gao M, Lindson N, Hartmann-Boyce J, Watkinson P, Young D, Coupland C, Tan PS, Clift AK, Harrison D, Gould DW, Pavord ID, Hippisley-Cox J. 2021. Association between pre-existing respiratory disease and its treatment, and severe COVID-19 : a population cohort study. The Lancet Respiratory Medicine. Volume 9. Issue 8. Pages 909-923. Link: https://www.sciencedirect.com/science/article/pii/S2213260021000953

2. Ebinger JE, Achamallah N, Ji H, Claggett BL, Sun N, Botting P, Nguyen TT, Luong E, Kim EH, Park E, Liu Y, Rosenberry R, Matusov Y, Cheng S. 2020. Pre-existing traits associated with COVID-19 illness severity. PLOS ONE. Volume 15. Issue 7. Link: https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0236240

3. Clerkin KJ, Fried JA, Raikhelkar J, Sayer G, Griffin JM, Masoumi A, Jain SS, Burkhoff D, Kumaraiah D, Rabbani L, Schwartz A, Uriel N. 2020. COVID-19 and Cardiovascular Disease. Circulation. Volume 141. Issue 20. 1648-1655. Link: https://www.ahajournals.org/doi/full/10.1161/CIRCULATIONAHA.120.046941

4. Bansal M. 2020. Cardiovascular disease and COVID-19. Diabetes & Metabolic Syndrome: Clinical Research & Reviews. Volume 14. Issue 3. Pages 247-250. Link: https://www.sciencedirect.com/science/article/pii/S1871402120300539

5. Keet CA, Keller JP, Peng RD. 2017. Long-Term Coarse Particulate Matter Exposure Is Associated with Asthma among Children In Medicaid. American Journal of Respiratory and Critical Care Medicine. Volume 197. Issue 6. Link: https://www.atsjournals.org/doi/full/10.1164/rccm.201706-1267OC

6. Zhang Z, Zhu D, Cui B, Ding R, Shi X, He P. 2019. Association between particulate matter air pollution and lung cancer. Thorax. Volume 75. Issue 1. Link: https://thorax.bmj.com/content/75/1/85.abstract?casa_token=WgCNf_ABi7UAAAAA:Mgiwe-yu6kq3wWYA-wPq8bwQEUFFuAHQHyFAG-rPd45Pe-d-HoKjUqsoQpFIPy9csGVrhBoCVsk

7. White AJ, Keller JP, Zhao S, Carroll R, Kaufman JD, Sandler DP. 2019. Air Pollution, Clustering of Particulate Matter Components, and Breast Cancer in the Sister Study: A U.S.-Wide Cohort. Environmental Health Perspectives. Volume 127. Issue 10. Link: https://ehp.niehs.nih.gov/doi/full/10.1289/EHP5131

8. Tecer LH, Alagha O, Karaca F, Tuncel G, Eldes N. 2008. Particulate Matter (PM2.5, PM10-2.5, PM10) and Children's Hospital Admissions for Asthma and Respiratory Diseases: A Bidirectional Case-Crossover Study. Journal of Toxicology and Environmental Health. Volume 71. Issue 8. Link: https://www.tandfonline.com/doi/full/10.1080/15287390801907459?casa_token=PvhhGxydNi0AAAAA%3AzAqYE_DsJTM5wE02YY91zJFTMxzYl6mn0wI_7uheFFOiEkpAvHlQDb1JkZtKi5_Vr4nr99QAph5A

9. Comunian S, Dongo D, Milani C, Palestini P. 2020. Air Pollution and COVID-19: The Role of Particulate Matter in the Spread and Increase of COVID-19's Morbidity and Mortality. Int J Environ Res Public Health. Volume 17. Issue 12. Link: https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7345938/

10. Shafinaz N, Yip CW, Ibrahim N, Jaafar MH, Rashid ZZ, Mustafa N, Hamid HHA, Chandru K, Latif MT, Saw PE, Lin CY, Alhasa KM, Hashim JH, Nadzir MSM. Particulate Matter (PM2.5) as a potential SARS-COV-2 carrier. Nature. Volume 11. Issue 2508. Pages 1-6. Link: https://www.nature.com/articles/s41598-021-81935-9
