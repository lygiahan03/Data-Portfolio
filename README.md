# International Trade Overview and Vietnam Outlook
# 1. Project Background
	
 The International Trade in Goods (ITG) dataset, published by the International Monetary Fund (IMF) in August 2025, provides a comprehensive view of global trade flows.
	
 This project leverages the dataset to analyze and synthesize both the global trade landscape and Vietnam’s trade outlook. The objective is not only to present descriptive statistics, but to transform complex trade indicators into actionable business insights and strategic recommendations.
	
 Through this analysis, the project demonstrates how international trade dynamics—such as the balance between exports and imports, the role of price deflators versus volume indices, and the dominance of CIF and FOB shipping terms—affect business risks, opportunities, and policy directions.
	
 **The value of this project within the portfolio:**
 
   • Integrate multiple tools and methods: from data cleaning in Python, to SQL-based measurement, to Tableau visualizations.
 
   • Bridge technical analysis with strategic insights, making trade data directly relevant for businesses and policymakers.
 
   • Showcase decision-oriented outcomes, such as how importers and exporters can manage price volatility, and how Vietnam can strengthen logistics and policy frameworks.
	
 **Key deliverables include:**
		
   • An interactive Tableau dashboard for visualization and exploration.
		
   • SQL queries demonstrating trade measurement and deep-dive analysis.
  
   • Python scripts for robust data cleaning and preparation.

# 2. Data Structure & Initial Checks
	
 International Trade in Goods's dataset is structured as a large database. For the purpose of analysis, I queried into 6 main tables have 4 ones entitled relationships and 2 are separate for further analysis.
	
Below are 6 tables: type_of_trade, trade_frequency, indicator_country, type_of_transformation, vietnam, export_vs_import
<img width="944" height="452" alt="image" src="https://github.com/user-attachments/assets/0cf7724d-d391-4136-8ce0-df8ae36ef94c" />
<img width="4320" height="2430" alt="image" src="https://github.com/user-attachments/assets/40ae7017-6eac-456a-b786-00f0774817f3" />

# 3. Executive Summary
	
	
 International Trade Overview and Vietnam Outlook (Based on IMF International Trade in Goods Dataset, 2025)
	
 This dashboard presents an integrated analysis of international trade dynamics with a focused lens on Vietnam’s trade profile. The insights highlight both structural patterns in global trade and Vietnam’s positioning within this landscape, offering implications for businesses, policymakers, and investors.
	
	
 **Global Trade Landscape**
		
  **• Balance:** Global trade is broadly even (195 exporters vs. 196 importers), but slightly higher import participation signals demand exceeding supply, creating opportunities for exporters and incentives for domestic substitution.
		
  **• Trade Composition:** Goods trade dominates, with balanced participation in price and volume indices across 92 countries. This indicates a stable match between demand and supply, reducing pricing uncertainty.
	
 **• Transformation:** Imports are largely shipped under CIF terms, while exports rely more on FOB. This underscores the global importance of risk and cost allocation in shipping, with direct implications for contract design, logistics costs, and business margins.
	
	
 **Vietnam Trade Outlook**
		
  **• Trade Type:** Vietnam’s trade is concentrated in price deflator-based exports and imports, reflecting its dual role as an export-driven economy and a significant importer of raw materials and intermediate goods.
	  
   **• Index Sensitivity:** With **62.5% of trade indices based on price deflators**, Vietnam is highly exposed to global price fluctuations.
			
   **○ Exporters** face revenue volatility tied to international prices.
			
   **○ Importers** bear higher risks, as rising global costs inflate input expenses, compress margins, and raise consumer prices.
   
   **• Transformation:** Vietnam’s reliance on CIF (period & YoY) and FOB (period & YoY) arises from limited logistics capacity, capital constraints, and the need for risk management. This highlights the urgency of strengthening domestic logistics, shipping, and insurance sectors to capture more value from global trade.

<img width="2798" height="1436" alt="image" src="https://github.com/user-attachments/assets/2670e5d7-c75e-46db-af77-1e23ef5034b6" />



# 4. Insights 

**A. World Trade**
	
 **• Exports vs. Imports**
	
 The global trade structure remains relatively balanced, with exports reported in 195 countries and imports in 196 countries. However, the marginal predominance of imports suggests a persistent reliance on external supply, signaling that international demand slightly exceeds supply availability. This highlights two business implications:
		
  **a. Opportunity for Exporters:** Countries with competitive export capabilities can leverage this demand gap to expand market penetration.
		
  **b. Incentives for Domestic Substitution:** Policymakers and domestic producers are incentivized to develop local industries to substitute part of the unmet import demand, especially in strategic goods.
	
	
 **• Type of Trade**
	
 Imports and exports of goods represent the most widely adopted trade forms globally, with 92 countries actively participating in both price deflator and volume index measures. The relative symmetry in these participation levels indicates a well-functioning demand–supply mechanism where exporters can effectively match buyers at competitive prices. For businesses, this reflects reduced market distortion risk, ensuring greater predictability for trade planning, contract pricing, and supply chain stability.

<img width="552" height="484" alt="image" src="https://github.com/user-attachments/assets/056de79d-eea9-4fe3-a92f-8b355fe5d66f" />

	
 **• World Transformation**
	
 **- Imports** are predominantly shipped under **Cost, Insurance, and Freight (CIF)** terms, which shifts responsibility and costs onto exporters until the goods reach the importer’s port.
	
 **- Exports** are more frequently conducted under **Free on Board (FOB)**, placing greater responsibility on buyers for insurance and shipping.
	- The most common traded categories include imports of goods, volume index, and price deflator, primarily under CIF arrangements.
	- The prevalence of CIF and FOB terms, across both period-over-period and year-over-year changes, demonstrates the strong reliance on standardized shipping frameworks. From a business perspective, this underlines the importance of risk allocation strategies in international contracts and the need for enterprises to strengthen capabilities in managing logistics costs and currency volatility tied to CIF and FOB contracts.

<img width="1666" height="626" alt="image" src="https://github.com/user-attachments/assets/20cb6031-116b-450e-bc54-10464aafef06" />


**B. Vietnam Trade**
	
 **• Type of Trade**
	
 Vietnam’s trade structure is characterized by strong engagement in **exports of goods (price deflator)** and **imports of goods (price deflator)**. This reflects Vietnam’s positioning as both an export-driven economy and a significant importer of raw materials, technology, and intermediate goods essential for domestic production.

<img width="586" height="376" alt="image" src="https://github.com/user-attachments/assets/a4de5eec-0053-4c7c-a15c-6ccdc41cd233" />

 **• Index Type**
	
 Price deflators account for **62.5%** of Vietnam’s trade index, compared to **37.5%** for volume indexes. This heavy reliance on deflators underscores Vietnam’s **high sensitivity to global price fluctuations.**
		
  ○ For **exporters,** this means that shifts in international commodity prices or exchange rates have a disproportionate effect on revenue performance. Exporters face both opportunities (when global prices rise) and risks (when demand softens due to higher costs).
		
  ○ For **importers,** the exposure is even more critical. Since Vietnam imports significant volumes of raw materials, energy, and intermediate goods for domestic production, any increase in world prices immediately inflates input costs. This can compress profit margins, raise production costs for manufacturers, and ultimately affect domestic consumer prices. Importers therefore must adopt hedging strategies, supplier diversification, and long-term contracts to reduce exposure to volatile global markets.

<img width="628" height="452" alt="image" src="https://github.com/user-attachments/assets/a7f90653-a9fc-49d5-84e9-819a82578c6d" />

  
	From a business impact perspective, this structure means that both ends of Vietnam’s trade ecosystem are highly vulnerable to external shocks—making trade resilience and financial risk management central to sustaining competitiveness.


**• Transformation**
Vietnam’s top four transportation and pricing frameworks — CIF (period and YoY) and FOB (period and YoY) — differ from the global trend. 



**1. CIF (period & YoY)**
	• Ensures importers benefit from logistical convenience and reduced upfront complexity.
	• Simplifies budgeting and supplier relations, yet may compress margins due to higher bundled pricing.


**2. FOB (period & YoY)**
	• Enables exporters to limit exposure to unpredictable freight and insurance costs.
	• Frees up capital and consolidates their focus on production, not logistics.

<img width="1708" height="1118" alt="image" src="https://github.com/user-attachments/assets/e26dc204-e391-4d62-9f79-31ef0801f1a3" />


This suggests that Vietnam balances both seller-and-buyer responsible shipping terms more evenly, reflecting the country’s transitional role between manufacturing-driven exports and import reliance for production inputs. For businesses, this creates opportunities in logistics services, supply chain financing, and risk management tailored to Vietnamese trade flows.





