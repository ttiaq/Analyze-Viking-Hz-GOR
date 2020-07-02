# Analyze-Viking-Hz-GOR
Analyze GOR trends for Viking muti-stage frac horizontal wells

I used AccuMap as a starting point to get production data from IHS for all wells and save as a csv file and then import the csv file to here using Pandas.

#### My initial thoughts are:
- Get P10,  P25, median (P50), P75, P90 and average GOR trends for all wells; 
- Compare the distribution with 2,000 scf/stb (which was used in previous years for Viking), and determine if we need to change this cut-off;
- Compare last 3 month average GOR (or a longer timeframe) with the new cut-off to re-group HGOR/LGOR wells.

#### Deliverable/output from this code:
- A chart with historical GOR for all wells, along with P10, P25, P50, P75, P90 and average trends on top of them.
- An excel file with historical average GOR as well as last 3 month average GOR, last 6 month average GOR and last 12 month average GOR for each well.
- A chart with GOR tiers for HGOR/LGOR groupings, grouped by historical GOR of each well.
- A chart with GOR tiers for HGOR/LGOR groupings, grouped by last 12 month average GOR of each well.
- A chart with GOR tiers for HGOR/LGOR groupings, grouped by last 6 month average GOR of each well.

#### Requirement
- Plotly
