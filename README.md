# North America Energy Industry
 Analyze data available for N.A Energy Industry

# Project Objectives and Dataset Source

**Objective:** This project is created to explore, analyze, and understand the current energy production from renewable energy sources in North America.

**Analytics Type:** Descriptive Analytics. Thus, this project will summarize key features of the dataset to describe what happened in the past and provide digestible snapshots for visualization purposes.

**Data Type:** Structured data (Nemerical and Categorical), Non time-series. Since it's a structured dataset, the clean dataset will be stored in a SQL database such as SQL Elephant or PostgreSQL.

**Visualization Method:** Python libraries such as MatplotLib, Seaborn. In addition, a dashboard will also be created using Power BI.

**Data Source:** A static dataset (not streaming) called "PowerPlantsRenewGE1MW_NorthAmerica_201708.xlxs" was obtained from Government of Canada website, https://open.canada.ca/data/en/dataset/490db619-ab58-4a2a-a245-2376ce1840de

Dataset includes:

*   Stations with installed capacipy of more than 1MG electrical energy generated from renewable energy sources.
*   Data were collected for all countries in North America
*   Renewable Energy sources include: biomass, hydroelectric, pumped-storage hydroelectric, geothermal, solar, and wind.

# Brief Overview of Final Results

**Questions to answer:**

* Capacity of each country
* Capacity of each State
* Capacity by source of each country

**Results summary for the period between 2000-2017:**

* Within North America, U.S is the leader in electrical power production with 67.8% contribution to the total capacity produced within North America. Canada follows with 27.5% and finally Mexico with 4.8%.
* Within Canada, the top 3 provinces that produce electrical power are Quebec (44,402 MW), follows by British Columbia (17,642 MW) and Ontario (15,996 MW). The rest of the provinces produce less than 7000 kW each, thus making up small percentage in the contribution to the total power production. The breakdown of Capacity by source for each state is also provided. For example, Hydroelectric power is the main energy source in Canada and is most produced in Quebec, BC, Ontario, Newfoundland, and BC in descending order. * The second most important energy source in Canada is Wind, which is most produced in Ontario, Quebec, and Alberta in descending order. Solar energy source is mainly produced in Ontatio.
* Within US, the top 3 states that produce electrical power are California (34,199 MW), follows by Washington (25,000 MW) and Texas (23,152 MW). The rest of the states produce less than 12000 kW each. The breakdown of Capacity by source for the top 20 states are also provided. For example, Hydroelectric power is the main source in Washington, Oregon, Newyork, and Arizona.
* Within Mexico, the top 3 territories that produce electrical power are Chiapas (4860 MW), follows by Oaxaca (2702 MW) and Nayarit (2543 MW). The rest of the territories produce less than 1800 kW each. The breakdown of Capacity by source is also provided. For example, Hydroelectric power is the main source in Chiapas, Nayarit, Guerrero, Sinaloa, etc.
* US has the diversified power industry. The energy is produced from 10 major sources. The top 5 major sources are Wind, Hydroelectric, Solar, Pumped Storage, and Biomass in the descending order.
* Canada is much more restricted to only 4-5 energy sources. The majority of power is produced from Hydroelectric, follow by Wind. A much smaller amount of energy is produced from Solarand Biomass.
* Mexico is much more restricted to only 2 energy sources, Hydroelectric and Wind.

**Next Step**

* Load clean dataset onto Elephant SQL (PostgreSQL).
* Join with other datasets and create insightful dashboard.
