# dsc-project-phase-3-
# Background
The H1N1 and seasonal flu dataset contains information about individuals who participated in the 2009-2010 National Health and Nutrition Examination Survey (NHANES) conducted by the Centers for Disease Control and Prevention (CDC).
# Project overview
For this project, we will use classification algorithms to predict H1N1 vaccine acceptance.
# Main objective
* To build a classification model to predict whether an individual will presumably get H1N1 vaccine or not.
* # Specific objectives
* To import and clean the dataset to prepare the data for analysis and modeling.

* Model the data using Decision trees, Random Forest, and Logistic Regression.
To perform feature selection of our dataset.</br>
Below are some CRISP-DM steps we followed in our analysis.
# 1) Business Understanding
Businesses in the healthcare industry can gain insights into the demographic, socioeconomic, and health-related factors that are associated with H1N1 vaccine uptake. This information can be used to develop targeted marketing campaigns and vaccination programs that are more effective in reaching and persuading specific groups of people to get vaccinated. As the world struggles to vaccinate the global population against COVID-19, an understanding of how people’s backgrounds, opinions, and health behaviors are related to their personal vaccination patterns can provide guidance for future public health efforts. We aim to predict whether people got H1N1 vaccines using data collected in the National 2009 H1N1 Flu Survey.
# 2.)Data understanding
 The dataset was collected to study the prevalence and determinants of the H1N1 and seasonal flu vaccinations among the US population. 
  The data description (column names) are also found in https://www.drivendata.org/competitions/66/flu-shot-learning/
# 3.) Data Exploration
We are  just exploring and trying to understand our data.<br>
This includes :
**i)Visualisation of the numerical variables**
![download](https://github.com/learn-co-curriculum/dsc-data-visualization-with-pandas/assets/109750154/cde1e1e5-18cb-450f-b319-d3ba6e7bf901)
**ii)Exploratory data analysis**
Here, we are trying to see see how our columns behave for example checking how various variables affect **H1n1 Vaccine**</br>
**a) Age group**</br>
 </br>
![Sheet 1](https://github.com/learn-co-curriculum/dsc-data-visualization-with-pandas/assets/109750154/435b1634-873f-43f4-9cfe-dc4135269faa) </br>
**b)Marital Status**</br>
 </br>
![Sheet 6](https://github.com/learn-co-curriculum/dsc-data-visualization-with-pandas/assets/109750154/d1d176f2-d838-4f35-a861-9e703d6b7b50) </br>
**c)The level of education**</br>
 </br>
![Sheet 2](https://github.com/learn-co-curriculum/dsc-data-visualization-with-pandas/assets/109750154/0e5cab0b-600d-4f77-a639-afe1795a8fba) </br>
**d)Home ownership.**</br>
 </br>
![Sheet 4](https://github.com/learn-co-curriculum/dsc-data-visualization-with-pandas/assets/109750154/f17a90e1-91fc-4c14-befb-eacd10e853d7)<br>
**e)Gender**</br>
 </br>
![Sheet 5](https://github.com/learn-co-curriculum/dsc-data-visualization-with-pandas/assets/109750154/d84de0ae-4bd1-49db-8fda-daf589aa0440)
# 4) Data preparation .
This is just trying to put our data in a form that is good for the model, this invloves: </br>
1. Checking for and dealing with  missing values . </br>
2. Checking for and removing multicollinearity. </br>
3. Data encoding (Label-encoding, One-Hot encoding)  </br>
# 5) Modelling and evaluation.
Here we are trying to now fit our data into a model into different models  and evaluating our different models.
In our notebook we use the following : </br>
1. Logistic Regression. </br>
2. Decision Trees. </br>
3. Random Forest. </br>
After evaluation of all these , we found decision trees to be the best model, with an accuracy of **83%**.
# Findings
* Age is a significant predictor of H1N1 vaccine uptake, with older adults more likely to get vaccinated compared to younger adults.

* Health behaviors such as wearing a face mask, washing hands frequently, and avoiding crowded places during an outbreak are associated with increased H1N1 vaccination uptake.

* Certain chronic medical conditions such as asthma and diabetes are associated with increased H1N1 vaccination uptake.

* Married individuals were more likely to get vaccinated compared to those who are unmarried.

* The employed were more likely to get vaccinated compared to those who are unemployed or not in the labor force.
# Recommendations

* Use of sensitisation and targeted marketing campaigns to address the specific demographic and socioeconomic factors associated with H1N1 vaccine uptake. This could include tailor-making campaigns for specific age groups and economic classes.

* Increasing the geographical access to vaccination by making it more accessible to people in different locations. An instance would be offering it in schools, worship centres and community centres.

* Offering incentives such as discounted health insurance premiums to promote the uptake of the vaccine.

* Demystifying myths and misinformation that exists concerning the vaccination, that could contribute to hesitancy in uptaking the vaccine.

* Partnering with public health agencies to develop and implement vaccination programs in areas that are not easily accessible. This could be implemented by the use of mobile vaccination clinics.


