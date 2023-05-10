# Analyzing the Canadian Government's Initiatives to Reduce Carbon Footprint

##### Introduction

This project aims to analyze the effectiveness of the initiatives taken by the Canadian government to manage greenhouse gas (GHG) emissions, energy consumption, and production, with a specific goal of achieving net zero emissions by 2050.

##### Datasets

Three datasets were used in this project:

###### 1. Green House Gases (GHG) by Federal Facilities and Fleets Dataset
This dataset includes two CSV files spanning 2005-2021, detailing the Canadian Government's facilities and their respective energy use and emissions. It also contains information about GHG emissions by federal fleets. This data was obtained from the Government of Canada's open data portal and is licensed under the Open Government License - Canada. Additionally, we utilized the Climate Watch Historical Emissions data, containing sector-level GHG emissions data for 194 countries and the European Union from 1990-2019.

###### 2. Electricity and Gas Consumption Dataset
This dataset provides information on Canada's total electricity and gas consumption, divided by province and year, from 2012 to 2021. It was sourced from the Canadian Centre for Energy Information.

##### 3. North American Renewable Integration Study (NARIS) Dataset
This dataset offers data on North American countries' energy production. It includes information about all energy-producing locations, whether renewable or conventional, spanning from 2010 to 2050.

##### Data Cleaning

We performed data cleaning to ensure the quality and consistency of the data. This involved removing null values, cleaning numeric columns, and standardizing the province columns for merging. Additional columns were added as needed for data visualization using the Geojson library.

##### Summarizing Results
###### Findings on GHG emissions
Emissions for government facilities have been reduced over the past decade.
Diesel is the most used fuel, and its use has remained constant.
Ontario generates the most emissions, while Yukon causes the least, in line with their respective populations.
Government facilities produce 22.8% of the country's GHG emissions.
Canada is one of the few nations with decreasing emissions when compared globally.
###### Findings on energy consumption
Alberta and Ontario consume the most energy.
Alberta has the highest industrial natural gas consumption, while Ontario leads for residential natural gas consumption. Nova Scotia has the least combined consumption.
Quebec has both the highest industrial and residential electricity consumption. Conversely, Nunavut has the least combined consumption.
###### Findings on energy production
Quebec and Ontario lead in both total energy production capacity and generation.
Dependence on Coal to produce energy is reducing as time passes.
Hydroelectricity is the most used renewable energy, but wind energy is predicted to catch up by 2038.
Renewable energy production is predicted to surpass non-renewable energy by 2046.
Distributed solar power is expected to increase threefold by 2036.
CO2 emissions continue to rise, but the rate of increase is decreasing every year.

##### Conclusion

Our findings indicate that Canada is making progress towards its goal of net-zero emissions by 2050 by dialling down emissions and focusing on increasing renewable energy dependency. However, the country faces challenges in getting citizens to join in sustainability goals. As a future scope, we could delve deeper into residential consumption and industrial emissions policies to gain insights into effective reforms and those that require updating.
