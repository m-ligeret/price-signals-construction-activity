# Price Signals and Construction Activity

Markets provide a decentralized mechanism for allocating resources, a process often considered more efficient than centralized alternatives. This efficiency largely stems from a central feature of markets: **prices**. Following the insights of **Hayek and the Austrian School**, prices convey dispersed information by signaling high demand or constrained supply. In this framework, prices act as an aggregation of information mostly about demand, guiding economic agents’ decisions.


Applied to the housing and construction sector, this theory implies that **construction activity should respond to price signals**: areas experiencing increasing demand—reflected in rising prices—should attract new construction. These intuitions were later formalized within the neoclassical framework, where investment decisions respond to prices higher than the equilibrium.

This data science project seeks to provide empirical evidence on a central question:

**Is the decentralized supply of housing and non-residential buildings efficient?**  
Put differently, **do markets build where buildings are most needed?**

The theory of price-signals is often used to oppose any regulation of real estate prices, this project aim to tackle one specific argument of opponents to market regulation : prices are supposed to send signals to real estate developers. 

Let's note however that France's real estate market is not a completely "free market" as there exists municipal regulation on the use of land and buildings. 

---

## Data

This analysis relies on administrative data on building permits and prior declarations related to the creation of housing units, including those resulting from the conversion or rehabilitation of existing buildings.

Those dataset mainly covers the period **from 2013 onward**

- Ministère de la Transition écologique (France):  
  https://www.statistiques.developpement-durable.gouv.fr/catalogue?page=dataset&datasetId=6513f0189d7d312c80ec5b5b
  It includes the two datasets : creation of residential buildings and creation of non residential buildings 
  This dataset contains information on building permits (PC) and prior declarations (DP) related to the creation of housing units, including those created through the conversion or rehabilitation of pre-existing buildings.

- French Property Transaction Database (DVF – Demandes de Valeurs Foncières) processed by Cerema
  https://www.data.gouv.fr/datasets/dvf-open-data 
  It is the list of the real estate transaction that occured during the given period. 


---

## Some related papers 
Empirical research has extensively studied the relationship between price signals and housing investment at an aggregate level. This topic is often called "responsiveness to prices of housing supply". 

- **China**  Housing prices have been shown to significantly influence construction activity and investment dynamics.  
  https://pmc.ncbi.nlm.nih.gov/articles/PMC8931181/

- **OECD Countries**  Cross-country evidence indicates that residential investment responds strongly to price changes, although institutional and regulatory constraints may attenuate this relationship.  
  https://www.sciencedirect.com/science/article/pii/S105113771300020X?via%3Dihub#s0015

However, research that focused on this relation at level of analysis below national levels are quite rare, which prompted us to use more granular datasets to test the relation between prices and construction activity.

