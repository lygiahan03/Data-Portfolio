# Project: International Trade Overview and Vietnam Outlook
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
	
 International Trade in Goods's dataset is structured as a considerable large database which has 5.5k records. For the purpose of analysis, I queried the dataset into 6 main tables which have 4 ones entitled relationships (type_of_trade, trade_frequency, indicator_country, export_vs_import) and 2 ones (vietnam, type_of_transformation) are separate for further analysis.
	
Below are 4 ERD tables: type_of_trade, trade_frequency, indicator_country, export_vs_import
<p align="center">
  <img src="https://github.com/user-attachments/assets/0cf7724d-d391-4136-8ce0-df8ae36ef94c" 
       alt="ERD international trade Dashboard" 
       style="max-width:100%; height:auto;">
</p>
<p align="center">
  <img src="https://github.com/user-attachments/assets/719b4b75-a629-4114-8fab-7957ce5b7a05"
       alt="ERD international trade Dashboard" 
       style="max-width:100%; height:auto;">
</p>

# 3. Executive Summary
	
	
 International Trade Overview and Vietnam Outlook (Based on IMF International Trade in Goods Dataset, 2025)
	
 This dashboard presents an integrated analysis of international trade dynamics with a focused lens on Vietnam’s trade profile. The insights highlight both structural patterns in global trade and Vietnam’s positioning within this landscape, offering implications for businesses, policymakers, and investors.
	
	
 **A. Global Trade Landscape**
		
  **• Balance:** Global trade is broadly even (195 exporters vs. 196 importers), but slightly higher import participation signals demand exceeding supply, creating opportunities for exporters and incentives for domestic substitution.
		
  **• Trade Composition:** Goods trade dominates, with balanced participation in price and volume indices across 193 countries. This indicates a stable match between demand and supply, reducing pricing uncertainty.
	
 **• Transformation:** Imports are largely shipped under CIF terms, while exports rely more on FOB. This underscores the global importance of risk and cost allocation in shipping, with direct implications for contract design, logistics costs, and business margins.
	
	
 **B. Vietnam Trade Outlook**
		
  **• Trade Type:** Vietnam’s trade is concentrated in price deflator-based exports and imports, reflecting its dual role as an export-driven economy and a significant importer of raw materials and intermediate goods.
	  
   **• Index Sensitivity:** With **62.5% of trade indices based on price deflators**, Vietnam is highly exposed to global price fluctuations.
			
   **○ Exporters** face revenue volatility tied to international prices.
			
   **○ Importers** bear higher risks, as rising global costs inflate input expenses, compress margins, and raise consumer prices.
   
   **• Transformation:** Vietnam’s reliance on CIF (period & YoY) and FOB (period & YoY) arises from limited logistics capacity, capital constraints, and the need for risk management. This highlights the urgency of strengthening domestic logistics, shipping, and insurance sectors to capture more value from global trade.


<p align="center">
  <img src="https://github.com/user-attachments/assets/2f564f02-774c-47c8-a4be-ab900823027f"
       alt="Dashboard" 
       style="max-width:100%; height:auto;">
</p>


# 4. In-depth Insights 

**A. World Trade**
	
 **• Exports vs. Imports**
	
 The global trade structure remains relatively balanced, with exports reported in 195 countries and imports in 196 countries. However, the marginal predominance of imports suggests a persistent reliance on external supply, signaling that international demand slightly exceeds supply availability. This highlights two business implications:
		
  **- Opportunity for Exporters:** Countries with competitive export capabilities can leverage this demand gap to expand market penetration.
		
  **- Incentives for Domestic Substitution:** Policymakers and domestic producers are incentivized to develop local industries to substitute part of the unmet import demand, especially in strategic goods.

 <p align="center">
  <img src="https://github.com/user-attachments/assets/5b274187-fd0f-423c-a739-a7648f90f6ff"
       alt="World Trade - Type of Trade" 
       style="max-width:100%; height:auto;">
</p>
	
 **• Type of Trade**
	
 Imports and exports of goods represent the most widely adopted trade forms globally, with 88-92 countries actively participating in both price deflator and volume index measures. The relative symmetry in these participation levels indicates a well-functioning demand–supply mechanism where exporters can effectively match buyers at competitive prices. For businesses, this reflects reduced market distortion risk, ensuring greater predictability for trade planning, contract pricing, and supply chain stability.

<p align="center">
  <img src="https://github.com/user-attachments/assets/056de79d-eea9-4fe3-a92f-8b355fe5d66f"
       alt="World Trade - Type of Trade" 
       style="max-width:100%; height:auto;">
</p>
	
 **• World Transformation**
	
 **- Imports** are predominantly shipped under **Cost, Insurance, and Freight (CIF)** terms, which shifts responsibility and costs onto exporters until the goods reach the importer’s port.
	
 **- Exports** are more frequently conducted under **Free on Board (FOB)**, placing greater responsibility on buyers for insurance and shipping.
	
 - The most common traded categories include imports of goods, volume index, and price deflator, primarily under CIF arrangements.
	
 - The prevalence of CIF and FOB terms, across both period-over-period and year-over-year changes, demonstrates the strong reliance on standardized shipping frameworks.

<p align="center">
  <img src="https://github.com/user-attachments/assets/20cb6031-116b-450e-bc54-10464aafef06"
       alt="World Trade - World Transformation" 
       style="max-width:100%; height:auto;">
</p>	
 
 From a business perspective, this underlines the importance of risk allocation strategies in international contracts and the need for enterprises to strengthen capabilities in managing logistics costs and currency volatility tied to CIF and FOB contracts.
 
 
**B. Vietnam Trade**
	
 **• Type of Trade**
	
 Vietnam’s trade structure is characterized by strong engagement in **exports of goods (price deflator)** and **imports of goods (price deflator)**. This reflects Vietnam’s positioning as both an export-driven economy and a significant importer of raw materials, technology, and intermediate goods essential for domestic production.

<p align="center">
  <img src="https://github.com/user-attachments/assets/a4de5eec-0053-4c7c-a15c-6ccdc41cd233"
       alt="Vietnam Trade - Type of Trade" 
       style="max-width:100%; height:auto;">
</p>

 **• Index Type**
	
 Price deflators account for **62.5%** of Vietnam’s trade index, compared to **37.5%** for volume indexes. This heavy reliance on deflators underscores Vietnam’s **high sensitivity to global price fluctuations.**
		
  - For **exporters,** this means that shifts in international commodity prices or exchange rates have a disproportionate effect on revenue performance. Exporters face both opportunities (when global prices rise) and risks (when demand softens due to higher costs).
		
  - For **importers,** the exposure is even more critical. Since Vietnam imports significant volumes of raw materials, energy, and intermediate goods for domestic production, any increase in world prices immediately inflates input costs. This can compress profit margins, raise production costs for manufacturers, and ultimately affect domestic consumer prices. Importers therefore must adopt hedging strategies, supplier diversification, and long-term contracts to reduce exposure to volatile global markets.

<p align="center">
  <img src="https://github.com/user-attachments/assets/a7f90653-a9fc-49d5-84e9-819a82578c6d"
       alt="Vietnam Trade - Index Type" 
       style="max-width:100%; height:auto;">
</p>

From a business impact perspective, this structure means that both ends of **Vietnam’s trade ecosystem are highly vulnerable to external shocks** — making trade resilience and financial risk management central to sustaining competitiveness.


**• Transformation**

Vietnam’s top four transportation and pricing frameworks — CIF (period and YoY) and FOB (period and YoY) — differ from the global trend. 



**1. CIF (period & YoY)**
	
 • Ensures importers benefit from logistical convenience and reduced upfront complexity.
	
 • Simplifies budgeting and supplier relations, yet may compress margins due to higher bundled pricing.


**2. FOB (period & YoY)**
	
 • Enables exporters to limit exposure to unpredictable freight and insurance costs.
	
 • Frees up capital and consolidates their focus on production, not logistics.

<p align="center">
  <img src="https://github.com/user-attachments/assets/e26dc204-e391-4d62-9f79-31ef0801f1a3"
       alt="Vietnam Trade - Transformation" 
       style="max-width:100%; height:auto;">
</p>

This suggests that Vietnam balances both seller-and-buyer responsible shipping terms more evenly, reflecting the **country’s transitional role between manufacturing-driven exports and import reliance for production inputs**. For businesses, this creates opportunities in logistics services, supply chain financing, and risk management tailored to Vietnamese trade flows.





