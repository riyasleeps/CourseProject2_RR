Weather Events Analysis
Overview
This R script aims to provide a comprehensive analysis of weather event data, shedding light on the events that have the most significant economic consequences and health impacts across the United States. By examining various weather-related variables, the script delves into understanding the implications of these events on both economic and public health sectors.

Data
The analysis hinges on a rich dataset encompassing detailed information on weather events. Key variables such as event type (EVTYPE), property damage (PROPDMG), crop damage (CROPDMG), injuries (INJURIES), and fatalities (FATALITIES) are essential for a thorough examination. The dataset should be structured in CSV format, ensuring the presence of pertinent columns necessary for robust analysis.

Economic Consequences
One pivotal aspect of the analysis involves aggregating property and crop damage data attributed to each weather event type. By discerning the top 10 events with the most substantial economic repercussions, the script aims to provide insights into the financial toll incurred by these events. Additionally, it visualizes the cost of damage for each event type through a meticulously crafted bar chart, highlighting the distinct impacts of property and crop damage.

Health Impact
Understanding the health ramifications of weather events is crucial for effective mitigation strategies. The script meticulously aggregates injury and fatality data associated with each weather event type. By identifying the top 20 events with the most significant health impacts, it offers valuable insights into the toll these events exact on public health. Through an intuitive bar chart visualization, the script illuminates the total number of fatalities and injuries for each event type, aiding in understanding the severity of their health consequences.

Requirements
To execute the analysis seamlessly, ensure that your environment meets the following requirements:

R (version >= 3.0.0)
ggplot2
dplyr
tidyr
