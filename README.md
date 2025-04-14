# Hedging Hydrogen Data Package

Scenario data supporting the paper: Hedging Hydrogen: Planning and Contracting Under Uncertainty for a Green Hydrogen Producer, 2025.

Submitted to Elsevier.

Authors: Owen Palmer (a,b), Hugo Radet (b), Simon Camal (a), Jalal Kazempour (c), Robin Girard (a)

(a) PSL University, Mines Paris - Centre PERSEE; 
(b) Verso Energy
(c) Technical University of Denmark (DTU)

## Data Files Descriptions 
da = day ahead market price (€/MWh) <br />
dem = hydrogen demand (MWh)<br />
ppa = hourly availability factor / production factor (/max capacity)

## In-Sample Set Descriptions 
Expected Value Problem, Fixed Demand = x1 scenario with average day ahead price (70€/MWh yearly average) and capacity factors. Standard demand scenario. <br />
Used for Solutions: *D_EVP(NA)*, *D_PE*, *D_PE(GS)*.

Expected Value Problem, Uncertain Demand = x10 even year day-ahead scenarios. Standard demand scenario only.<br />
Used for Solutions: *D_PE(dem)*, *D_PE(GS,dem)*.

Fixed Demand = x25 randomised scenarios, although with a fixed demand profile.<br />
Solutions: *S_*$\beta$*0(NA)*, *S_*$\beta$*0.9*, *S_*$\beta$*0.9(GS)*, *S_*$\beta$*0.9(NA)*.

Uncertain Demand =  x25 randomised scenarios with randomised seasonal demand changes.<br />
Solutions: *S_*$\beta$*0.9(dem)*, *S_*$\beta$*0.9(GS,dem)*.

## Out-of-Sample Set Descriptions
NOTE - out of sample sets are split into two files of 508, 492 scenarios for each set to reduce computational burden of initial loading.

Fixed Demand = x1000 x25 randomised scenarios with a fixed demand profile.<br />

Uncertain Demand = x1000 randomised scenarios with randomised seasonal demand changes.<br />

## Original Data Sources 
[1] ENTSOe, ENTSOe Transparency Platform https://transparency.entsoe.eu/ 
[2] Renewables Ninja, https://www.renewables.ninja/ 
