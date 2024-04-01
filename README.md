# HIV-AIDS-Data-Exploration
HIV (Human Immunodeficiency Virus) is the virus that attacks the human immune system. If it is not treated properly, it can progress to AIDS. Once the HIV virus enters the human body, it becomes a lifelong disease. While there is no perfect medicine to completely cure it, medication can help mitigate the effects of the virus. Study shows that late 1800 this disease jumped from Chimpanzee. 

Over the years, it has spread across Africa and has subsequently disseminated throughout the world. In the United States, it was first observed in the mid-1980s. HIV, the virus associated with AIDS, has emerged as one of the most significant global health and developmental challenges since its initial documentation in 1981. Approximately 39 million people worldwide are living with HIV, and tens of millions have died due to AIDS. These statistics align with the Sustainable Development Goals (SDGs), adopted in 2015, which aim to end the AIDS epidemic by 2030 as part of SDG Goal 3: "ensure healthy lives and promote well-being for all at all ages."
To gain a deeper statistical understanding, I am conducting exploratory data analysis on HIV data obtained from UNESCO and WHO.

<h1>Description of Dataset</h1>
Data Sources:  https://www.kaggle.com/datasets/imdevskp/hiv-aids-dataset/code
##There are six CSV files, I will use the first four for this project:

cases.csv: Number of cases among adults aged 19-45.

deaths.csv: Number of deaths due to HIV/AIDS.

pediatric.csv: ART (Antiretroviral Therapy) coverage among people living with HIV estimates.

living.csv:  Number of people living with HIV/AIDS.

coverage.csv: Prevention of mother-to-child transmission estimates.

prevention.csv: ART (Antiretroviral Therapy) coverage among children estimates. 

<h1>Case dataframe</h1>: Let's delve into the initial dataset, which comprises seven columns: Country, Year, Count, Count_median, Count_min, Count_max, and WHO Region. The Year column contains distinct values spanning 2018, 2010, 2005, and 2000. I focused on the Count_median for analyzing data relationships

![top_5_countries_cases](https://github.com/githubPratima/HIV-AIDS-Data-Exploration/assets/98135375/30a50b7b-8a7b-4fca-b3af-3ab47357fc01) 

Next I explore the number of cases across regions defined by WHO. We see that the majority of cases (61%) are in Africa.  This is not surprising, given the poverty rate and lack of education, HIV aids have been more prevalent in African countries. 

![distribution_Of_cases](https://github.com/githubPratima/HIV-AIDS-Data-Exploration/assets/98135375/ffae4836-6361-46b5-8b03-d001ecedd7e4)




<h1>Observation from all above visulizations</h1>
1. <strong>Bargraph</strong>  Illustrates the top 10 countries worldwide with the highest number of HIV cases per thousand. Eswatini leads with a rate of 105.6, followed by Lesotho 
                             and Botswana at 94.7 and 94.4 respectively. Zimbabwe also ranks high with a rate of 72.1.

2. <strong>Piechart</strong> According to the pie chart, Africa has the highest number of cases, followed by the Americas with the second highest, and then the Western Pacific region
     
   
3.  <strong>Heatmap</strong> We see that, across all the years, Africa has more HIV cases. However, we see that the total number is decreasing, which is good news. But the cases have almost doubled in the Mediterranean region from 2010 to 2018.
    
<h1>Death dataset</h1> The "Death" dataset consists of columns including Country, Year, Count, Count_median, Count_min, Count_max, WHO Region, and Percentage. Within this dataset, the Count_min, Count_median, and Count_max columns contain missing values, which have been effectively handled using the fillna method.                      

![Screenshot 2024-03-31 190528](https://github.com/githubPratima/HIV-AIDS-Data-Exploration/assets/98135375/ca38019c-987c-44a8-bf95-b354674e46e9)

First I create a heatmap to visualize the total numbers of deaths over the years by WHO regions. We see that, across all years, Africa has more HIV deaths. However, we see that the total number is decreasing, which is good news. But the cases have almost doubled in the Mediterranean region from 2010 to 2018. 

![testII](https://github.com/githubPratima/HIV-AIDS-Data-Exploration/assets/98135375/5bb43ea1-7c25-4d2e-be88-af466fce34e7) 

Next I analyze the trends in death by countries (top 11 countries). We see that for almost all countries deaths have been decreasing over the years.  

![testII](https://github.com/githubPratima/HIV-AIDS-Data-Exploration/assets/98135375/a2dcc1d0-0a3b-4005-81f2-cd6b90abd2a6)

Next I create maps of Africa with deaths by year. We see that majority of deaths are in South Africa. 

![testII](https://github.com/githubPratima/HIV-AIDS-Data-Exploration/assets/98135375/62a3c074-bf8e-4c01-a8bc-8a69fcac21b6)

Further, the heat map confirms the death by year for African countries. 

![testII](https://github.com/githubPratima/HIV-AIDS-Data-Exploration/assets/98135375/13c0b29b-b4c2-45d4-96d1-0e74c31e7420)
 

 <h1>Prevention dataset</h1> Next I analyze the prevention dataset. This data set is about Antiretroviral Therapy
 
 ![Screenshot 2024-04-01 144433](https://github.com/githubPratima/HIV-AIDS-Data-Exploration/assets/98135375/dd4db0d2-3cb3-4bc2-81eb-1ba8238f6148)

 First I make a bar graph by WHO regions on number of total dosages of  Antiretrovirals. Unsurprisingly, Africa has received the most. 
 
 ![testII](https://github.com/githubPratima/HIV-AIDS-Data-Exploration/assets/98135375/f9112a2a-84a9-41bd-9ec0-e87b7c1c3ab8)

However, the pie charts of number of dosages needed in highest in African region. 
 ![prevention](https://github.com/githubPratima/HIV-AIDS-Data-Exploration/assets/98135375/861befc4-511b-4394-9bce-6b62d6f2905e)


 <h1>Living dataset</h1> Next I analyze the living dataset. This data is about number of people living with HIV/AIDS.

 ![livingtrend_for_all_WHO_region](https://github.com/githubPratima/HIV-AIDS-Data-Exploration/assets/98135375/bec5ccf7-c8eb-4d0e-ab0a-6b374abdf100)

 We see that, African region has some 81% of the population living with HIV Aids in the world. 

 <h1>Observation and overall inshights from all above visulizations</h1>
1.      Africa bears the highest HIV/AIDS burden, notably in Eswatini, while Eastern Mediterranean and Europe are less affected. Europe sees rising cases, while Africa and the Americas show declines, and South-East Asia and Western Pacific have mixed trends.

2.      Africa records the highest deaths, but the trend is decreasing. The Americas, particularly Brazil, have significant fatalities, while Europe, especially Ukraine, witnesses a concerning rise in deaths. The Eastern Mediterranean, like Pakistan, sees an upward trend.

3.      Africa faces the highest demand for pediatric ART, with varied coverage, while Europe generally presents lower pediatric needs but better coverage. South Africa and Nigeria top the list in requirements.


