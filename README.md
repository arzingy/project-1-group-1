# Project 1: Alzheimer's
We've decided to use [Alzheimer’s Prediction Dataset (Global)](https://www.kaggle.com/datasets/ankushpanday1/alzheimers-prediction-dataset-global?resource=download) dataset.

## Group:
- Borsukov, Arseniy
- Singh, Aaron
- Nguyen, Kieran
- Farladansky, Gennadiy
- Santacruz, Johanna
- Morris, Rache

## Presentation
[Link to the slides](https://docs.google.com/presentation/d/1djM73LDHUUjZm_VcKeZdbhJ_lm5EEcYZZ1fmvbCRd1k/edit?usp=sharing)

[Rough Draft Analysis](https://docs.google.com/document/d/12Xi_vrRZmNh0fCJ4JRGEdpCOceKxe4oyO44_b4MkrN8/edit?usp=sharing)

## Questions:
Overarching Question: What factors can reliably be used to predict an alzheimer's Diagnosis?

1. Is Alzheimer's hereditary, do individuals with a family history of Alzheimer's get it at a higher rate than those with no family history?
2. Does country or gender have an impact on Alzheimer's Disease diagnosis?
3. Can cognitive test scores alone serve as a reliable predictor of Alzheimer's disease?
4. Does age have an impact on Alzheimer's Diagnosis?
5. Does BMI and dietary habits have an impact on Alzheimer's?
6. How does cholesterol levels affect an Alzheimer's Diagnosis?

## Analysis:
1. What contributing factors can be used to predict an Alzheimer’s Diagnosis?  
   1. Alzheimer’s is a disease that causes are not widely known, in this analysis we used data from “Alzheimer’s Prediction Dataset (Global)” that has data from over 74,000 individuals from various countries that either have a positive or negative Alzheimer’s diagnosis. Using this data we have chosen to focus on these categories (BMI/Dietary Habits, Age, Family History, Country/Gender, Cognitive Test Scores, and Cholesterol Levels)  in order to determine whether they can or cannot be used to predict an individual's likelihood of developing Alzheimer’s.

2. Can BMI and Dietary Habits predict a person’s chances of being diagnosed with Alzheimer’s? 


1. As shown in the Box and Whisker Plot above, BMI distribution between individuals with a positive or negative diagnosis is very similar.   
   1. A statistical test was conducted to further analyze the significance of the gathered data.  
   2. Our T-statistic given is (-0.4641) for the above data. Since \-0.4641 is very close to 0, this confirms that the two groups have almost no difference in BMI.  
   3. The T-statistic measures the difference between the mean BMI of those diagnosed with Alzheimer’s and those not diagnosed, relative to the difference in the data.  
   4. Our P-value tells us whether the difference is statistically significant. The P-value of the above data is 0.6426.  
   5. Since 0.6426 is much greater than 0.05, this means the data is not statistically significant.  
   6. To conclude, we fail to reject the null hypothesis. BMI does not appear to have a significant impact on Alzheimer’s diagnosis.
<figure>
   <img
   src="/Images/BMI/BMI.png">
</figure>

2. As shown in the stacked bar chart below, Alzheimer’s diagnosis among individuals with varied dietary habits appears to be very similar.  
   1. To further analyze the data, we conducted a Chi-square test to measure the relationship between dietary habits and Alzheimer’s diagnosis. This test measures the difference between the observed frequencies and the expected frequencies if there were no relationship between the two groups.  
   2. A higher Chi-square value would suggest a strong relationship between the two variables.  
   3. The Chi-square statistic returned was 1.5262, which is on the lower end, suggesting that the difference in Alzheimer’s diagnosis across dietary habits is small.  
   4. Our P-value of 0.4662 for the above data further confirms that there is no significant relationship between dietary habits and Alzheimer’s diagnosis,  
   5. Any P-value greater than 0.05 means the difference is not statistically significant and 0.4662 is much greater.  
   6. In conclusion, we fail to reject the null hypothesis, meaning that dietary habits do not have a significant impact on Alzheimer’s diagnosis according to our data.  
   7. Therefore, BMI nor Dietary Habits can predict a person’s chances of being diagnosed with Alzheimer’s. Other factors are more likely to play a more significant role.
<figure>
  <img
  src="/Images/DietaryHabits/dietary.png">
</figure>
   

3. How does age have an impact on cognitive health?  
     
   It is no surprise that older persons are more susceptible to Alzheimer's disease because, even as young adults, we forget things like our early years. As scientists investigate why Alzheimer's primarily affects older adults, they have discovered that age-related changes include blood vessel damage, inflammation, atrophy (shrinking) of specific brain regions, the generation of unstable molecules known as free radicals, and mitochondrial dysfunction (a breakdown of energy production within a cell). These kinds of studies and databases, which scientists are still learning about, assist to clarify how aging may impact your health as you mature.  
     
1. The average age of the Alzheimer's patients in this data collection is 72, with ages ranging from 50 to 94  
2. 52,012 people between the ages of 50 and 100 have been diagnosed with Alzheimer's disease  
3. 22,741 people between the ages of 50 and 94 have **Not** been diagnosed with Alzheimer's disease
<figure>
  <img
  src="/Images/Age/age_distr.png">
</figure>
<figure>
  <img
  src="/Images/Age/age_alz.png">
</figure>

4. Can Family History of Alzheimer’s be used to predict an individual’s likelihood of being diagnosed with Alzheimer’s?  
   1. Many diseases are hereditary, so we decided to break down the data by both family history of Alzheimer’s and whether or not the individual had a positive or negative diagnosis. This data was then broken into pie charts, to better illustrate the impact of Family History on an individual’s Alzheimer’s diagnosis.  
   2. **Null Hypothesis (H₀):** There is no significant correlation between one’s family history of Alzheimer's and an individual’s likelihood of a positive Alzheimer’s diagnosis.  
   4. <figure>
        <img
        src="/Images/FamilyHistory/whole_pie.png">
      </figure> 
      1. 70% of participants from the dataset do not have a family history of Alzheimer’s.  
      2. 30% of participants from the dataset do have a family history of Alzheimer’s  
   5. <figure>
        <img
        src="/Images/FamilyHistory/yes_alz_pie.png">
      </figure> 
      1. Of the 30% of participants that do have a family history of Alzheimer’s, 52% of participants had a positive Alzheimer’s Diagnosis.  
   6. <figure>
        <img
        src="/Images/FamilyHistory/no_alz_pie.png">
      </figure> 
      1. Of the 70% of participants that did not have a family history of Alzheimer’s, only 37% had a positive Alzheimer’s diagnosis.

   7. The large and varied sample size of the data set, leads me to believe that family history can be a strong indicator of a potential Alzheimer’s diagnosis. This conclusion is based on the staggering 15% increase in positive Alzheimer’s Diagnosis, between those who do not have a family history of Alzheimer’s and those who do.  
5. Country/Gender  
   <figure>
      <img
      src="/Images/Country/countries.png">
   </figure>  
   1. The top 3 leading countries with Alzheimer are Russia (1906), India (1883) and Brazil (1865)  
   2. The bottom 3 countries with Alzheimer are Japan (1273), Canada (1267) and Sweden (1262)  
   3. Average number of cases among 20 countries is 1535.65

   <figure>
      <img
      src="/Images/Gender/gender.png">
   </figure> 

   4. 13 out of 20 countries show women are affected by Alzheimer’s Disease more than men  
   5. Average number of cases among men is 766.85  
   6. Average number of cases among women is 768.8  
   7. Men and women are equally affected by Alzheimer’s Disease  
   8. There is no statistical evidence suggesting that country and gender are significant factors in predicting or diagnosing Alzheimer’s Disease

6. Cholesterol Level  
   1. **Null Hypothesis (H₀):** There is no association between Alzheimer's disease and cholesterol levels.  
   2. **Methodology:** A chi-square test of independence was performed to examine the relationship between Alzheimer's disease and cholesterol levels. The chi-square test compares the observed frequencies of the categories to the expected frequencies if the variables were independent.  
   3. **Chi-Square Test Results:**  
      1. **Chi-square statistic:** 0.3195112054318619  
      2. **P-value:** 0.57  
      3. **Degrees of Freedom:** 1  
   4. **Graphs:**  
      1. <figure>
              <img
              src="/Images/Cholesterol/cholesterol_general.png">
         </figure> 
      2. <figure>
              <img
              src="/Images/Cholesterol/chol_pies.png">
         </figure>   
   5. **Interpretation:** The chi-square statistic of 0.3195112054318619 and a p-value of 0.57 suggest that the observed frequencies of cholesterol levels among individuals with and without Alzheimer's disease are very close to the expected frequencies if there were no association between the variables. Since the p-value is greater than the significance level of 0.05, we fail to reject the null hypothesis. This indicates that there is no significant association between Alzheimer's disease and cholesterol levels. The pie charts support this conclusion, showing similar proportions of cholesterol levels among individuals with and without Alzheimer's disease. The visual similarity reinforces the statistical finding that there is no notable association between the variables.  
   6. **Conclusion:** Based on the chi-square test results and the graphical analysis, we conclude that there is no significant association between Alzheimer's disease and cholesterol levels. The data does not provide strong evidence to suggest a relationship between these variables. Future research with larger sample sizes and additional factors may provide more insights into the potential connections between Alzheimer's disease and cholesterol levels.  
7. Cognitive test Score  
   1. **Null Hypothesis (H₀):** There is no significant difference in cognitive test scores between individuals with and without Alzheimer's disease.  
   2. **Methodology:** An independent t-test was performed to compare the mean cognitive test scores of the two groups: individuals with Alzheimer's disease and those without. The significance level was set at 0.05.  
   3. **T-Test Results:**  
      1. **T-statistic:** \-0.3111  
      2. **P-value:** 0.76  
   4. **Graphs:**  
      1. <figure>
              <img
              src="/Images/CognitiveTestScore/cognitive_test.png">
         </figure>  
      2. <figure>
              <img
              src="/Images/CognitiveTestScore/cogn_mean.png">
         </figure>    
   5. **Interpretation:** The t-statistic of \-0.3111 and a p-value of 0.76 suggest that the difference in mean cognitive test scores between individuals with and without Alzheimer's disease is not statistically significant. Since the p-value is greater than the significance level of 0.05, we fail to reject the null hypothesis. This indicates that there is no significant difference in cognitive test scores between the two groups. The bar graph supports this conclusion, showing very similar average cognitive test scores for individuals with and without Alzheimer's disease. The pie charts visualize the distribution of cognitive test scores within each group, further reinforcing the statistical finding that there is no notable difference between the variables. Both bars are of similar height, indicating that the average cognitive test scores for both groups are very close to each other, with only a slight difference of 0.0468 points.  
   6. **Conclusion:** Based on the t-test results and the graphical analysis, we conclude that there is no significant difference in cognitive test scores between individuals with and without Alzheimer's disease. The data does not provide strong evidence to suggest a relationship between Alzheimer's disease and cognitive test performance. Future research with larger sample sizes and additional factors may provide more insights into the potential connections between Alzheimer's disease and cognitive test scores.
