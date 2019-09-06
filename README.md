
# Multi-factor Model
---

This project is a production ready prototype model that 
  - builds a cross-sectional statistical risk model using PCA, which is used to build a portfolio along with a number of momentum, mean reversion, and sentiment alpha factors 
  
<img src="assets/explained_variance.PNG" alt="drawing" width="300px"/> 

<img src="assets/factor_returns.PNG" alt="drawing" width="300px"/>

  - universe: US equities, top 500 in terms of dollar volume
  - evaluates the alpha factors, combining the promising signals into a single alpha vector <br/> 
  
<img src="assets/factor_returns_quantile.PNG" alt="drawing" width="600px"/>

  - evaluates a number of approaches to constructing the optimal portfolio given objective/constraints 
  
<img src="assets/port_holdings.PNG" alt="drawing" width="300px"/> 

<img src="assets/port_risk_exposures.PNG" alt="drawing" width="300px"/>
  
**note:** uses end of day pricing data from Quotemedia and sector data from Sharadar, which could not be shared due to licensing restrictions

