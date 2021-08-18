# Data Engineering

*Data Lake* : sinble database instance which contains data from all around 
an organization (a group and bigger). Different kind of data: financial, delivery,
supplier, engine data, customer data, and so on.

**Advantage**: allows developer to make a single connection string to the *lake*
and they can creat data-driven insights in a centralized repository (if have access).

## Description of datasets (8)
- RUL (Remaining useful Life) for ESN (Engine Serial Number), it is the 'Y' we want to predict to
  unscheduled maintenance or identify issues (that are decreasing URL faster than expected)
- Flight data (from 4 datasets): engine measurements from 4 airline (AIC,FRON,PGS,AXM).
  Can be used to determine health of mechanical engine of a plane
- Location Data: they are codes called [ICAO](https://en.wikipedia.org/wiki/ICAO_airport_code)
  Useful to understand where are flying when data is collected
- Manufacturing Data: Data for 3 parts. Key measurements at certain operations in production
- MBOM (Manufacturing Bill of Material): matches every serial numbered part to respective engine via
  ESN serial number (which tells what engines have been used).
## Description of task
*Combine all data listed into a single table*
Tools: Excel, Tableau (I've used before), DataIku (Never used before). Recommendation:
Excel for maximum learning (granular understanding of data analytics) and Tableau/DataIku
as Industry grade tools. Here I've get *Data Glossary* which I relate to table description
column name, description and units. I think it's very important to know about the data you
are working with because there can be incompabilities or even some data cleaning insights.
