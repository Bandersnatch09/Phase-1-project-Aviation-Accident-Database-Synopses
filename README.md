# Aviation-Accident-Database-Synopses -phase 1 project
<img src="cockpit.jpg" alt="Cockpit" width="650" height="450">

### I.Overview
This project reviews data from the NTSB aviation accident database contains information from 1962 upto 2023 about civil aviation accidents and selected incidents within the United States, its territories and possessions, and in international waters .As the company expands into new industries, it acknowledges the crucial need to assess and manage the risks linked to aircraft operations. Although the aviation sector is profitable, it involves inherent risks that require careful analysis to ensure well-informed purchasing decisions.

### II.Business Understanding
The company seeks to broaden its portfolio by venturing into the aviation sector, intending to acquire and manage aircraft for both commercial use and private uses. The objective is to pinpoint the aircraft that carry the most risk, thereby ensuring safety through the actions to be taken and reducing potential liabilities. This information will guide the purchasing decisions for the new aviation division, focusing on safety and reliability.

### III.Data Understanding
The dataset includes temporal data with incident dates and information on accident identification from 
[National Transportation Safety Board (NTSB)](http://www.ntsb.gov/) <br>
[Kaggle NTSB aviation accident dataset](https://www.kaggle.com/datasets/khsamaha/aviation-accident-database-synopses) 
upto *2023* such as distinct event identifiers and inquiry kinds. 

### Methods
This project uses descriptive analysis in several forms to attempt to understand major causes of Aviation Accidents and Various exploratory diagnostis analyses to investigate the correlations between different entries and the region/states thet we're mostly involved in Aviation accidents <br>
The project also majorly includes various aspects of Data cleaning
* Handling Missing values
* Checking for duplicates
* Fixing structural issues

### Results
Examining the NTSB accident data from the past four decades reveals a noticeable trend of declining fatal accidents and fatalities, highlighting increased air travel safety over the last 40 years ,a significant spike in fatalities may have happened in 2001 due to the tragic 9/11 events
<img src="Visualisations/Trend fatal accidents.png" alt="Trend" width="650" height="450">
From the next plot we can formulate an understanding on which are the big three makes with the most fatalities
Approximately 26% of fatal accidents involve Cessna aircraft, followed by Piper with 19%, and Beech with 9%.
<img src="Visualisations/Make fatal accidents.png" alt="Trend" width="650" height="450">
#### Seeing which Engine types are most involved in Aviation accidents
<img src="Visualisations/Piechart Make.png" alt="Trend" width="650" height="450">

From the next plot we can then establish that the Make which was "CESSNA" together with the engine type "Reciprocating" was related and they had an inter-relationship by being the leading make and engine types involved in most Aviation incidences rrspectively
<img src="Visualisations/Engine vs make-Heatmap.png" alt="Trend" width="650" height="450">

We can see That the leading percentage of fatal injuries occur mostly during the VMC or rather(Visual Meteorological Conditions) then followed byIMC (Instrument Meterological Conditions)<br>
While practically the UNK(Unknown) does not contribute a lot <br>
<img src="Visualisations/weatherconditions.png" alt="Trend" width="650" height="450">
The following are the top 10 states with the higest rate of Fatal Accidents
<img src="Visualisations/Top10 states.png" alt="Trend" width="650" height="450">
Heatmap showing the density of the states with the most Fatal Accidents
<img src="Visualisations/Region.heatmap.png" alt="Trend" width="650" height="450">



