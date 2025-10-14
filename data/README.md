# data

Place data file(s) in this folder. Add the dimensions (rows and columns).

Then, include codebooks (variables, and their descriptions) for your data file(s)
using the following format.

## energy.csv

The original dataset consists of the energy consumption, expenditure, and price by source per state in the United States from 1960 to 2019. The data comes from the U.S. Energy Information Administration.

We filter this down to the year 2019 to analyze the most recent data available. This leaves 51 observations, one for each state and one for Washington DC, and 84 variables.

- `State`: Identifies the state where the data is collected and reported
- `Year`: Year that the report was made
- `Consumption.{industry}.{type}`: {type} consumed by the {industry} sector in billion BTU
- `Expenditure.{industry}.{type}`: {type} expenditures in the {industry} sector in million dollars.
- `Price.{industry}.{type}`: {type} price in the {industry} sector in dollars per million BTU

*Industries:* Commercial, Electric Power, Industrial, Refinery, Residential, Transportation

*Types:* Coal, Distillate Fuel Oil, Geothermal, Hydropower, Kerosene, Petroleum, Natural Gas, Other Petroleum Products, Solar, Wind, Wood