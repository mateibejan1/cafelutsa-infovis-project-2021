# Cafelutsa: Information Visualization Project 2021
Meet THE TEAM: Matei Bejan, Valentin Calinescu, Andrei Zugravu

We are former undergraduate colleagues and we have all worked together on numerous projects in the past with great final results.

About the dataset:

The World Development Indicators from the World Bank contains 1346 social and economic indicators for 247 countries and geopolitical groups, collected over 55 years, from 1960 to 2015. Thus, it presents a total of 13585 samples.

The initial dataset is unsuitable for modelling and thus requires some prior restructuring. The raw data presents one sample per feature per country per year. Our first action was to parse the data set and to group all features by year and country. For this we have dropped the CountryCode and IndicatorCode columns and added a column for every feature. Next, we have discarded the Value column and placed the sample in its respective column. This way each sample will contain all indicators observed in a year, per every year, per every country.
