# Unicorn Companies Exploration
## by Salem Abu Alrub


## Dataset

 The data we are using is 'Unicorn Companies' dataset, contains private companies the took the name unicorn, that means the company got a valuation over a 1 billion US dollar, the data has 1074 entries, and 10 columns including the name of the company, the valuation, funding, county of origin, investors, the year founded and the year become unicorn.

 Data sourse: https://www.mavenanalytics.io/data-playground

 Data Wrangling notes:

1. some entries in the 'valuation' and 'funding' columns in Billion and some in Million, we need to unify the unit, we also need to remove the dollar sign, and change the type to int.
2. investors column to be renamed and splited to separate columns, and rename columns with space to get rid of the space.
3. year_founded and date joind to be changed to datatime type.
4. we need to make new column year_unicorn taking out only the year from the date of being unicorn, also change the type to data time.
5. Add feature 'duration_to_unicorn' subtracting the 'year founded' from the 'year unicorn'
6. 'city' column has 16 null values, we will copy the name from country.


## Summary of Findings

Summary of Main Findings:

The average time needed for a successful startup to be a unicorn is 7 years.

'Sequoia Capital China' is the most investor that funded a companies that became unicorn.

Industry Focus by City: The analysis shows that different cities have distinct industry focuses based on the amount of funding allocated to specific sectors. In San Francisco, the primary industries of focus are Fintech, followed by Internet software & services, and Customer & retail. Fintech stands out as the most attractive industry for investors in San Francisco.

No Clear Funding-Valuation Relationship: The data analysis suggests that there is no straightforward or direct relationship between the amount of funding a company receives and its valuation. This indicates that while certain industries may attract significant funding, it does not guarantee a proportionate increase in a company's valuation. Factors beyond funding, such as revenue, profitability, and market dynamics, also play a crucial role in determining valuation.

City Leadership in Unicorn Startups: San Francisco emerged as a leader in the creation of unicorn startups, reaching its first peak in 2014. Other cities began following this trend, with Beijing experiencing the largest peak in 2017. However, San Francisco regained its position as a leader in 2019 and 2021. This underscores the dynamic nature of the unicorn startup landscape, with cities competing for dominance.

Investment and Valuation Trends: San Francisco not only invested the most money in companies that achieved unicorn status but also had the highest total valuation for such companies. Beijing followed as the second-largest investor and valuation leader. Interestingly, New York, despite having the second-highest number of unicorn companies, did not necessarily correlate with higher funding or valuation.

In conclusion, this data exploration provided valuable insights into the relationship between funding, valuation, and city-level trends in the unicorn startup landscape. It highlights the complexity of factors influencing company valuation and the competitive nature of cities in nurturing and supporting startups. These findings can inform investment decisions and strategies for both investors and companies in the startup ecosystem.




## Key Insights for Presentation


Technology-related industries, such as Fintech, Software, E-commerce, and Artificial Intelligence, have the highest concentration of unicorn companies.
Emerging sectors like HealthTech and Clean Energy are also seeing a growing number of unicorn startups.
Traditional industries like Real Estate are less represented among unicorn companies.


The time it takes for a company to become a unicorn varies significantly by industry and market conditions.
On average, it takes around 7 years from founding to achieve unicorn status, but some startups achieve this status much faster due to other factors not included in our data.


The United States, particularly Silicon Valley, remains the global leader in unicorn companies, with a high concentration in cities like San Francisco and New York.
China, especially cities like Beijing and Shanghai, has seen a significant rise in unicorn startups, making it the second-largest unicorn ecosystem.
Other countries in Asia, such as India and Singapore, are also emerging as unicorn hubs.
European countries like the United Kingdom, Germany, and France have notable unicorn ecosystems, with London and Berlin as key cities.


Prominent venture capital firms like Sequoia Capital, Andreessen Horowitz, and Accel have consistently been major backers of unicorn companies.
