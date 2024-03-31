# HIV-AIDS-Data-Exploration
HIV (Human Immunodeficiency Virus) is the virus that attacks the human immune system. If it is not treated properly, it can progress to AIDS. Once the HIV virus enters the human body, it becomes a lifelong disease. While there is no perfect medicine to completely cure it, medication can help mitigate the effects of the virus. Study shows that late 1800 this disease jumped from Chimpanzee. 

Over the years, it has spread across Africa and has subsequently disseminated throughout the world. In the United States, it was first observed in the mid-1980s. HIV, the virus associated with AIDS, has emerged as one of the most significant global health and developmental challenges since its initial documentation in 1981. Approximately 39 million people worldwide are living with HIV, and tens of millions have died due to AIDS. These statistics align with the Sustainable Development Goals (SDGs), adopted in 2015, which aim to end the AIDS epidemic by 2030 as part of SDG Goal 3: "ensure healthy lives and promote well-being for all at all ages."
To gain a deeper statistical understanding, I am conducting exploratory data analysis on HIV data obtained from UNESCO and WHO.

<h1>Description of Dataset</h1>

##There are six CSV files:

cases.csv: Number of cases among adults aged 19-45.

deaths.csv: Number of deaths due to HIV/AIDS.

living.csv:  Number of people living with HIV/AIDS.

coverage.csv: Prevention of mother-to-child transmission estimates.

pediatric.csv: ART (Antiretroviral Therapy) coverage among people living with HIV estimates.

prevention.csv: ART (Antiretroviral Therapy) coverage among children estimates.

<h1>Case dataframe</h1>: Let's delve into the initial dataset, which comprises seven columns: Country, Year, Count, Count_median, Count_min, Count_max, and WHO Region. The Year column contains distinct values spanning 2018, 2010, 2005, and 2000. I focused on the Count_median for analyzing data relationships

![top_5_countries_cases](https://github.com/githubPratima/HIV-AIDS-Data-Exploration/assets/98135375/30a50b7b-8a7b-4fca-b3af-3ab47357fc01) 

![distribution_Of_cases](https://github.com/githubPratima/HIV-AIDS-Data-Exploration/assets/98135375/ffae4836-6361-46b5-8b03-d001ecedd7e4)

Upon further examination, I explored the percentage distribution of cases across different WHO regions.

![test](https://github.com/githubPratima/HIV-AIDS-Data-Exploration/assets/98135375/7adffefe-6b5f-4b46-a64e-8a0ef4882d1a) 

![testII](https://github.com/githubPratima/HIV-AIDS-Data-Exploration/assets/98135375/af4cd638-75c9-4329-b25e-64468f5a7886)

<h1>Observation from all above visulizations</h1>
1.  <strong>Bargraph</strong> illustrates the top 10 countries worldwide with the highest number of HIV cases per some unit of measurement. Eswatini leads with a rate of 105.6, followed by Lesotho and Botswana at 94.7 and 94.4 respectively. Zimbabwe also ranks high with a rate of 72.1.
2.   <strong>Piechart</strong> According to the pie chart, Africa has the highest number of cases, followed by the Americas with the second highest, and then the Western Pacific region
3.  <strong>Linechart</strong> Trend of cases is slightly decreases in africa and americas trends seems decreading at  till 2010 and it came in constant pattern..cprrect the sentences 
    and others seems no change at all.
4.  <strong>Linechart</strong> For the trend of cases by country, Botswana, Malawi, Namibia, Uganda, and Zimbabwe are experiencing a decrease, while Eswatini, Mozambique, and South Africa are showing an increase.                          




