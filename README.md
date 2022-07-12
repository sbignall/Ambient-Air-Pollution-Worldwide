# Visualization of Global Ambient Air Quality Mortality and Loss of Daily Adjusted Life Years (2016)


&nbsp;

## Investigation Data 

Two main overall measurements were used: Ambient Air Pollution (AAP) attributable death rate, as a direct measurement of lives lost due to AAP, and AAP-Attributable loss of DALY (Disability-Adjusted Life Years), which functions as a measure of the years of life lost in a population as a result of ambient air pollution, and measures in a broader manner the effect of AAP on a countrys population. PM2.5 (Air particles with a diameter under 2.5 micrometres) concentration is a highly important measurement of pollution included in WHO air-pollution-related datasets and was used here as a measurement of air pollution at the country-wide level.

Further datasets were used which I thought may relate to air pollution by country, these being Urban Population, Population Density, % of Women in the Workforce and GDP Per Capita. These data were considered to impact variables such as working hours, workplace safety standards, working hours and more, which in turn impact the amount of pollution created in a given area. The data sources are listed below:

 - AAP Attributable Death Rate (https://www.who.int/data/gho/data/indicators/indicator-details/GHO/ambient-air-pollution-attributable-death-rate-(per-100-000-population))
 - Ambient air pollution attributable DALYs (per 100 000 population) (https://www.who.int/data/gho/data/indicators/indicator-details/GHO/ambient-air-pollution-attributable-dalys-(per-100-000-population))
 - Concentrations of fine particulate matter (PM2.5) (https://www.who.int/data/gho/data/indicators/indicator-details/GHO/concentrations-of-fine-particulate-matter-(pm2-5))
 - Urban Population (https://data.worldbank.org/indicator/SP.URB.TOTL.IN.ZS)
 - Population Density (https://data.worldbank.org/indicator/EN.POP.DNST)
 - Female Workforce Participation Rate (https://data.worldbank.org/indicator/SL.TLF.CACT.FE.ZS)
 - GDP per Capita (https://data.worldbank.org/indicator/NY.GDP.PCAP.CD)

The data above were all dated to 2016 as this is the latest year these measurements were all available in full.

&nbsp;
## Cleaning of Data

Raw data downloaded from these sources were cleaned in excel; removing unnecessary columns and rows, transposing data, and filtering by year. When saved in cleaned format the data were visualized in Tableau. Choropleths of the main variables were used to show global distribution, and in turn each were analyzed together with the POM2.5 Concentration, Urban Population, Female Workforce Participation rate and GDP per Capita to examine if any were significantly correlated. Dashboards of the most important/interesting findings were created.  
&nbsp;

## Summary

As expected, Ambient Air Pollution (AAP) attributable death rate and AAP-Attributable loss of DALY (Disability-Adjusted Life Years) were both highly correlated (R^2 = 0.71). Interestingly, there was a much higher correlation with AAP attributable death rate and POM2.5 Concentration than AAP-Attributable loss of DALY and POM2.5 Concentration (r^2 = 0.64 vs r^2 = 0.35). R-Squared scores between all other correlations were below 0.2, surprisingly. In the case of all these variables, really it is most likely that these are too broad generally to be meaningful, and that the key assessment that longer exposure to urban environments as a result of work or residence would produce higher mortality and loss of life years was incorrect. Some key takeaways from the datasets relating to this are:

 - Rural POM2.5 Concentrations are  higher than urban Concentrations in many countries (e.g Nigeria (47.1 μg / m3 vs 72.8 μg / m3)
 - Some countries with relatively high GDP per Capita consist of highly dense urban areas (e.g. Singapore) 
 - Large countries may have a few cities with high populations and high pollution but enough rural citizens spread out to equal or more this population

   
