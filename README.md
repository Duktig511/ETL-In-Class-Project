# ETL-In-Class-Project
Birthrates among Adolescents Last 40yrs

A.  Overview

●	Possible reasons and effects of decline in birthrates among general female population and adolescent females(15-19)  worldwide.
●	Collection of Socioeconomic data points in past 20-30 years such as standard of living, population density, GDP per capita etc.
●	Consolidate sources from  various global establishments via parsing and aggregation of different features into single relational database.
●	Aggregate data points into more easily analyzed time periods such as by decade.


B. Sources and Extraction Method

●	Data: Country Statistics: Birth Rate,
Source:CIA Library
Source Link: https://www.cia.gov/library/publications/resources/the-world-factbook/rankorder/2054rank.html
Source Extraction Method: SQL/DB2
Scope:~2015, world-wide
●	Data:Contraceptive prevalence (% women 15-49) by country
Source:United Nations
Source Link: http://data.un.org/Data.aspx?d=WDI&amp;f=Indicator_Code%3aSP.DYN.CONU.ZS
Source Extraction Method: SQL/DB2
Scope:~1968-2014, world-wide
●	Data:Adolescent fertility rate (births per 1,000 women ages 15-19), worldwide
Source:World Bank
Source Link: http://data.un.org/Data.aspx?q=rate&amp;d=WDI&amp;f=Indicator_Code%3aSP.ADO.TFRT
Source Extraction Method: SQL/DB2
Scope:~1960-2012, world-wide
●	Data:Country Population by Gender 1985-2005
Source:United Nations
Source Link:http://data.un.org/Data.aspx?d=GenderStat&amp;f=inID%3a5
Source Extraction Method: SQL/DB2
Scope:~1960-2012, world-wide
●	Data:Annual % population growth by country
Source:United Nations
Source Link:http://data.un.org/
Source Extraction Method: SQL/DB2
Scope:~1960-2012, world-wide
●	Data:Country Statistics: Education Expenditures
Source:CIA Library
Source Link:https://www.cia.gov/library/publications/resources/the-world-factbook/rankorder/2206rank.html
Source Extraction Method: CSV
Scope:~1960-2012, world-wide


C. Data Parsing

●	Identify and parse out sub-populations in original data for improved data zooming


D. Data Normalization

●	Normal dates into broader “Decade” period to reduce disparity in timelines in data sources.
●	Create a “Rosetta Stone” to align and capture country Identification methods e.g. full name or abbreviation
●	 Regionalize countries based on either : geographic proximity, economic parity, or cultural similarity.
