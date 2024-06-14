# Long-term-investment-and-energy-procurement-risk-management

Scenario data supporting the paper: Long-term investment and energy procurement risk management planning under uncertainty for an electrolytic green hydrogen producer, 2024.

Submitted to Energy Economics.

Authors: Owen Palmer (a,b), Hugo Radet (b), Simon Camal (a), Robin Girard (a)

(a) Mines Paris - Centre PERSEE; 
(b) Verso Energy

## Data Files Descriptions 
da = day ahead market price (€/MWh) [1]<br />
dem = hydrogen demand (MW)<br />
ppa = hourly availability factor / production factor (/max capacity) [2]

## In-Sample Set Descriptions 
In-Sample Set 1 = x1 day-ahead scenario for 2018 re-centred at 70€/MWh yearly average. Standard demand scenario. <br />
Solutions: *D_AS(NA)* and *D_PE*.

In-Sample Set 2 = x10 even year day-ahead scenarios. Standard demand scenario only.<br />
Solutions: *S_*$\beta$*0(NA)(da,p)*, *S_*$\beta$*0.9(da,p)*, *S_*$\beta$*0.9(NA)(da,p)*, and Context's A, B and C in the prospective study.

In-Sample Set 3 = x15 even year day-ahead scenarios. Standard demand scenario and seasonal demand scenario.<br />
Solutions: *S_*$\beta$*0.9(da,p,dem)*

In-Sample Set 4 = x1 day-ahead scenario for 2018 re-centred at 70€/MWh yearly average. Standard demand scenario averaged by hour with seasonal demand scenario.<br />
Solutions: *D_PE(A.dem)*

## Out-of-Sample Set Descriptions
Out-of-Sample Set 1 = x20 odd-year scenarios. Standard demand scenario

Out-of Sample Set 2 = x20 odd-year scenarios. Seasonal demand scenario.

## Test Set Descriptions
Test Set 1 = Out-of-Sample Set 1 only<br />
Test Set 2 = Out-of-Sample Sets 1 & 2 Combined

## References 
[1] ENTSOe, ENTSOe Transparency Platform https://transparency.entsoe.eu/ 

[2] Renewables Ninja, https://www.renewables.ninja/ 
