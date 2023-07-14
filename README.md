
# DATA SOURCED:
Poudel, P. (2022). World Energy Consumption. Kaggle. 
    https://www.kaggle.com/datasets/pralabhpoudel/world-energy-consumption

## About Dataset
Data on Energy by Our World in Data

This dataset is a collection of key metrics maintained by Our World in Data. It is updated regularly and includes data on energy consumption (primary energy, per capita, and growth rates), energy mix, electricity mix and other relevant metrics.
🗂️ Download the complete Energy dataset : CSV | XLSX | JSON
Data sources

    Energy consumption (primary energy, energy mix and energy intensity): this data is sourced from a combination of two sources—the BP Statistical Review of World Energy and SHIFT Data Portal.
    Electricity consumption (electricity consumption, and electricity mix): this data is sourced from a combination of two sources—the BP Statistical Review of World Energy and EMBER – Global Electricity Dashboard.
    Other variables: this data is collected from a variety of sources (United Nations, World Bank, Gapminder, Maddison Project Database, etc.). More information is available in our codebook.

The complete Our World in Data Energy dataset

Our complete Energy dataset is available in CSV, XLSX, and JSON formats.

The CSV and XLSX files follow a format of 1 row per location and year. The JSON version is split by country, with an array of yearly records.

The variables represent all of our main data related to energy consumption, energy mix, electricity mix as well as other variables of potential interest.
Changelog

    On March 31, 2021, we updated 2020 electricity mix data.
    On September 9, 2020, the first version of this dataset was made available.

Data alterations

    standardize names of countries and regions. Since the names of countries and regions are different in different data sources, standardize all names to the Our World in Data standard entity names.
    recalculate primary energy in terawatt-hours. The primary data sources on energy—the BP Statistical Review of World Energy, for example—typically report consumption in terms of exajoules. recalculated these figures as terawatt-hours using a conversion factor of 277.8.
    calculate per capita figures. All of our per capita figures are calculated from our metric Population, which is included in the complete dataset. These population figures are sourced from Gapminder and the UN World Population Prospects (UNWPP).

License

All visualizations, data, and code produced by Our World in Data are completely open access under the Creative Commons BY license. You have the permission to use, distribute, and reproduce these in any medium, provided the source and authors are credited.

The data produced by third parties and made available by Our World in Data is subject to the license terms from the original third-party authors. We will always indicate the original source of the data in our database, and you should always check the license of any such third-party data before use.
Authors



## ABOUT DATASET
This data has been collected, aggregated, and documented by Hannah Ritchie, Max Roser and Edouard Mathieu.

The mission of Our World in Data is to make data and research on the world’s largest problems understandable and accessible. 

Roser, M.(2023).About.Our World In Data, a project of Global Change Data Lab.
    https://ourworldindata.org/about

## Columns and their description
|column | description|
|-------|------------|
|iso_code                 |ISO 3166-1 alpha-3 three-letter country codes|
|country                  | Geographic location |
|year                     | Year of observation |
|coal_prod_change_pct     | Annual percentage change in coal production |
|coal_prod_change_twh     |	Annual change in coal production, measured in terawatt-hours |
|gas_prod_change_pct      | Annual percentage change in gas production |
|gas_prod_change_twh      | Annual change in gas production, measured in terawatt-hours |
|oil_prod_change_pct      | Annual percentage change in oil production |
|oil_prod_change_twh      | Annual change in oil production, measured in terawatt-hours |
|energy_cons_change_pct   |	Annual percentage change in primary energy consumption |
|energy_cons_change_twh   |	Annual change in primary energy consumption, measured in terawatt-hours |
|biofuel_share_elec 	    |    Share of electricity consumption that comes from biofuels |
|biofuel_cons_change_pct    | 	Annual percentage change in biofuel consumption |
|biofuel_share_energy 	    |    Share of primary energy consumption that comes from biofuels |
|biofuel_cons_change_twh    | 	Annual change in biofuel consumption, measured in terawatt-hours |
|biofuel_consumption 	    |    Primary energy consumption from biofuels, measured in terawatt-hours |
|biofuel_elec_per_capita    | 	Per capita electricity consumption from biofuels, measured in kilowatt-hours |
|biofuel_cons_per_capita    | 	Per capita primary energy consumption from biofuels, measured in kilowatt-hours |
|carbon_intensity_elec 	    |    Carbon intensity of electricity production, measured in grams of carbon dioxide emitted per kilowatt-hour |
|coal_share_elec 	        |    Share of electricity consumption that comes from coal|
|coal_cons_change_pct 	|  Annual percentage change in coal consumption |
|coal_share_energy 	    |    Share of primary energy consumption that comes from coal |
|coal_cons_change_twh 	|    Annual change in coal consumption, measured in terawatt-hours |
|coal_consumption 	    |    Primary energy consumption from coal, measured in terawatt-hours|
|coal_elec_per_capita 	|    Per capita electricity consumption from coal, measured in kilowatt-hours |
|coal_cons_per_capita 	|    Per capita primary energy consumption from coal, measured in kilowatt-hours|
|coal_production 	    |    Coal production, measured in terawatt-hours
|coal_prod_per_capita 	|    Per capita coal production, measured in kilowatt-hours
|electricity_generation |	Electricity generation, measured in terawatt-hours
|biofuel_electricity 	|    Electricity generation from biofuels, measured in terawatt-hours
|coal_electricity 	    |    Electricity generation from coal, measured in terawatt-hours
|fossil_electricity 	|  Electricity generation from fossil fuels, measured in terawatt-hours. This is the sum of electricity generation from coal, oil and gas.|
|gas_electricity 	    |    Electricity generation from gas, measured in terawatt-hours|
|hydro_electricity 	    |    Electricity generation from hydropower, measured in terawatt-hours|
|nuclear_electricity 	|Electricity generation from nuclear power, measured in terawatt-hours|
|oil_electricity 	            |Electricity generation from oil, measured in terawatt-hours|
|other_renewable_electricity    |Electricity generation from other renewable sources, measured in terawatt-hours|
|other_renewable_exc_biofuel_electricity | Electricity generation from other renewable sources excluding biofuels, measured in terawatt-hours|
|renewables_electricity     |	Electricity generation from renewables, measured in terawatt-hours|
|solar_electricity 	        |Electricity generation from solar, measured in terawatt-hours|
|wind_electricity 	        |Electricity generation from wind, measured in terawatt-hours|
|energy_per_gdp 	        |Energy consumption per unit of GDP. This is measured in kilowatt-hours per 2011 international-$.|
|energy_per_capita 	        |Primary energy consumption per capita, measured in kilowatt-hours per year|
|fossil_cons_change_pct     |Annual percentage change in fossil fuel consumption|
|fossil_share_energy 	    |Share of primary energy consumption that comes from fossil fuels|
|fossil_cons_change_twh     |Annual change in fossil fuel consumption, measured in terawatt-hours|
|fossil_fuel_consumption    |Fossil fuel consumption, measured in terawatt-hours. This is the sum of primary energy from coal, oil and gas.|
|fossil_energy_per_capita| 	Per capita fossil fuel consumption, measured in kilowatt-hours. This is the sum of primary energy from coal, oil and gas.|
|fossil_cons_per_capita |	Per capita fossil fuel consumption, measured in kilowatt-hours. This is the sum of primary energy from coal, oil and gas.
|fossil_share_elec 	        |Share of electricity consumption that comes from fossil fuels (coal, oil and gas combined)|
|gas_share_elec 	         |Share of electricity consumption that comes from gas|
|gas_cons_change_pct 	A|nnual percentage change in gas consumption|
|gas_share_energy 	Share| of primary energy consumption that comes from gas|
|gas_cons_change_twh 	A|nnual change in gas consumption, measured in terawatt-hours|
|gas_consumption 	Prima|ry energy consumption from gas, measured in terawatt-hours|
|gas_elec_per_capita 	P|er capita electricity consumption from gas, measured in kilowatt-hours|
|gas_energy_per_capita 	P|er capita primary energy consumption from gas, measured in kilowatt-hours|
|gas_production 	Gas p|roduction, measured in terawatt-hours|
|gas_prod_per_capita 	P|er capita gas production, measured in kilowatt-hours|
|hydro_share_elec 	Share| of electricity consumption that comes from hydropower|
|hydro_cons_change_pct 	A|nnual percentage change in hydropower consumption|
|hydro_share_energy 	S|hare of primary energy consumption that comes from hydropower|
|hydro_cons_change_twh 	A|nnual change in hydropower consumption, measured in terawatt-hours|
|hydro_consumption 	Prima|ry energy consumption from hydropower, measured in terawatt-hours|
|hydro_elec_per_capita 	P|er capita electricity consumption from hydropower, measured in kilowatt-hours|
|hydro_energy_per_capita |	Per capita primary energy consumption from hydropower, measured in kilowatt-hours|
|low_carbon_share_elec 	S|hare of electricity consumption that comes from low-carbon sources. This is the sum of electricity f|rom re|ne|wab|les and nuclear
|low_carbon_electricity |	Electricity generation from low-carbon sources, measured in terawatt-hours. This is the sum of el|ectric|it|y g|eneration from renewables and nuclear power
|low_carbon_elec_per_capi|ta 	Per capita electricity consumption from low-carbon sources, measured in kilowatt-hours|
|low_carbon_cons_change_p|ct 	Annual percentage change in low-carbon energy consumption|
|low_carbon_share_energy |	Share of primary energy consumption that comes from low-carbon sources. This is the sum of primar|y ener|gy| fr|om renewables and nuclear
|low_carbon_cons_change_t|wh 	Annual change in low-carbon energy consumption, measured in terawatt-hours|
|low_carbon_consumption |	Primary energy consumption from low-carbon sources, measured in terawatt-hours|
|low_carbon_energy_per_ca|pita 	Per capita primary energy consumption from low-carbon sources, measured in kilowatt-hours|
|nuclear_share_elec 	S|hare of electricity consumption that comes from nuclear power|
|nuclear_cons_change_pct |	Annual percentage change in nuclear consumption|
|nuclear_share_energy 	S|hare of primary energy consumption that comes from nuclear power|
|nuclear_cons_change_twh |	Annual change in nuclear consumption, measured in terawatt-hours|
|nuclear_consumption 	P|rimary energy consumption from nuclear power, measured in terawatt-hours|
|nuclear_elec_per_capita |	Per capita electricity consumption from nuclear power, measured in kilowatt-hours|
|nuclear_energy_per_capit|a 	Per capita primary energy consumption from nuclear, measured in kilowatt-hours|
|oil_share_elec 	Share| of electricity consumption that comes from oil|
|oil_cons_change_pct 	A|nnual percentage change in oil consumption|
|oil_share_energy 	Share| of primary energy consumption that comes from oil|
|oil_cons_change_twh 	A|nnual change in oil consumption, measured in terawatt-hours|
|oil_consumption 	Prima|ry energy consumption from oil, measured in terawatt-hours|
|oil_elec_per_capita 	P|rimary energy consumption from oil, measured in terawatt-hours|
|oil_energy_per_capita 	P|er capita primary energy consumption from oil, measured in kilowatt-hours|
|oil_production 	Oil p|roduction, measured in terawatt-hours|
|oil_prod_per_capita 	P|er capita oil production, measured in kilowatt-hours|
|other_renewables_elec_pe|r_capita 	Per capita electricity consumption from other renewables, measured in kilowatt-hours|
|other_renewables_share_e|lec 	Share of electricity consumption that comes from other renewables|
|other_renewables_cons_ch|ange_pct 	Annual percentage change in energy consumption from other renewables|
|other_renewables_share_e|nergy 	Share of primary energy consumption that comes from other renewables|
|other_renewables_cons_ch|ange_twh 	Annual change in other renewable consumption, measured in terawatt-hours|
|other_renewable_consumpt|ion 	Primary energy consumption from other renewables, measured in terawatt-hours|
|other_renewables_energy_|per_capita 	Per capita primary energy consumption from other renewables, measured in kilowatt-hou|rs|
|per_capita_electricity |	Electricity consumption per capita, measured in kilowatt-hours|
|population 	Total pop|ulation|
|primary_energy_consumpti|on 	Primary energy consumption, measured in terawatt-hours|
|renewables_elec_per_capi|ta 	Per capita primary energy consumption from renewables, measured in kilowatt-hours|
|renewables_share_elec 	S|hare of electricity consumption that comes from renewables|
|renewables_cons_change_p|ct 	Annual percentage change in renewable energy consumption|
|renewables_share_energy |	Share of primary energy consumption that comes from renewables|
|renewables_cons_change_t|wh 	Annual change in renewable energy consumption, measured in terawatt-hours|
|renewables_consumption |	Primary energy consumption from renewables, measured in terawatt-hours|
|renewables_energy_per_ca|pita 	Per capita electricity consumption from renewables, measured in kilowatt-hours|
|solar_share_elec 	Share| of electricity consumption that comes from solar|
|solar_cons_change_pct 	A|nnual percentage change in solar consumption|
|solar_share_energy 	S|hare of primary energy consumption that comes from solar|
|solar_cons_change_twh 	A|nnual change in solar consumption, measured in terawatt-hours|
|solar_consumption 	Prima|ry energy consumption from solar, measured in terawatt-hours|
|solar_elec_per_capita 	P|er capita electricity consumption from solar, measured in kilowatt-hours|
|solar_energy_per_capita |	Per capita primary energy consumption from solar, measured in kilowatt-hours|
|gdp 	Total real gross |domestic product, inflation-adjusted|
|wind_share_elec 	Share| of electricity consumption that comes from wind|
|wind_cons_change_pct 	A|nnual percentage change in wind consumption|
|wind_share_energy 	Share| of primary energy consumption that comes from wind|
|wind_cons_change_twh 	A|nnual change in wind consumption, measured in terawatt-hours|
|wind_consumption 	Prima|ry energy consumption from wind, measured in terawatt-hours|
|wind_elec_per_capita 	P|er capita electricity consumption from wind, measured in kilowatt-hours|
|wind_energy_per_capita |	Per capita primary energy consumption from wind, measured in kilowatt-hours|
