# IoT_Analytics

## Deep Analytics, Visualitzation and Modelling

**Visualize and Analyze Energy Data**

**Smart energy usage**: Modeling patterns of energy usage by time of day and day of the year in a typical household whose electrical system is monitored by multiple sub-meters (3 submetrs this case) by using this Data Set: 
[Individual household electric power consumption Data Set](http://archive.ics.uci.edu/ml/datasets/Individual+household+electric+power+consumption)


**Data Attribute Information:**
**date:** Date in format dd/mm/yyyy

**time**: time in format hh:mm:ss

**global_active_power:** household global minute-averaged active power (in kilowatt)

**global_reactive_power:** household global minute-averaged reactive power (in kilowatt)

**voltage:** minute-averaged voltage (in volt)

**global_intensity:** household global minute-averaged current intensity (in ampere)

**sub_metering_1:** energy sub-metering No. 1 (in watt-hour of active energy). It corresponds to the kitchen, containing mainly a dishwasher, an oven and a microwave (hot plates are not electric but gas powered)

**sub_metering_2:** energy sub-metering No. 2 (in watt-hour of active energy). It corresponds to the laundry room, containing a washing-machine, a tumble-drier, a refrigerator and a light

**sub_metering_3:** energy sub-metering No. 3 (in watt-hour of active energy). It corresponds to an electric water-heater and an air-conditioner

**Data Set Information:**
This archive contains 2075259 measurements gathered in a house located in Sceaux (7km of Paris, France) between December 2006 and November 2010 (47 months).

**Notes:**

(global_active_power*1000/60 - sub_metering_1 - sub_metering_2 - sub_metering_3) represents the active energy consumed every minute (in watt hour) in the household by electrical equipment not measured in sub-meterings 1, 2 and 3.

The dataset contains missing values which is nearly 1,25% of the total observations. All calendar timestamps are present in the dataset but for some timestamps, the measurement values are missing: a missing value is represented by the absence of value between two consecutive semi-colon attribute separators. For instance, the dataset shows missing values on April 28, 2007.
