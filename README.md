# **Analyzing Food Price Patterns in Sri Lanka Using Data Mining Techniques**

## Overview
This group project explores **food price patterns in Sri Lanka** using **data mining and data visualization techniques** implemented in **R**. The study analyzes real-world food price data collected from multiple markets and regions to uncover trends, regional disparities, price volatility, and economic impacts on food security.

The project applies **unsupervised and supervised learning techniques**, including clustering, association rule mining, and logistic regression, alongside an interactive **R dashboard** to support data-driven decision-making.

---

## Dataset
The dataset is sourced from the **World Food Programme (WFP) Price Database**, accessed via the HDX platform. It contains food commodity prices recorded across Sri Lankan markets.

- **Source:** HDX / World Food Programme  
- **Format:** CSV  
- **Records:** ~13,000 (dashboard analysis sample used ~500)  
- **Coverage:** Multiple markets across Sri Lanka  
- **Currency:** LKR and USD  

### Key Variables
- Country  
- Market (Region/City)  
- Category (Cereals, Pulses, Oils, etc.)  
- Commodity  
- Price  
- Unit  
- Date  

---

## Project Components

### 1. Data Preparation
- Cleaning raw CSV data and removing invalid entries  
- Handling missing values and inconsistent formats  
- Converting categorical variables into factors  
- Encoding numerical features for modeling  

---

### 2. Data Mining Techniques

#### Clustering
- K-Means Clustering  
- Hierarchical Clustering  
- Elbow Method and Silhouette Score for cluster selection  

Used to group food commodities and markets based on price similarities.

#### Association Rule Mining
- Apriori Algorithm  
- Discovery of frequent itemsets and price co-occurrence patterns  

Used to identify food items that exhibit similar pricing behavior across markets.

#### Logistic Regression
- Binary and categorical price classification  
- Used to predict price bands (Low / Medium / High)  

---

### 3. Data Visualization & Dashboard
- Interactive R dashboard using **Shiny** and **Plotly**  
- Time-series analysis of food prices  
- Regional price comparison  
- LKR vs USD price visualization  
- Commodity-level volatility analysis  

---

## 🎥 Project Video Presentation
A recorded video presentation explaining the **dataset, methodology, dashboard, results, and conclusions** is available at the link below:

🔗 **Video Presentation (Google Drive):**  
👉 https://drive.google.com/drive/folders/1pQHuy0UwesEDgBbkf4sYbs7_iaNBC2bo?usp=sharing

---

## Key Findings
- Staple foods such as **rice and wheat flour** show consistent upward price trends  
- Urban markets (e.g., Colombo) generally have higher food prices than rural markets  
- Currency depreciation significantly impacts food affordability  
- Imported food items display higher price volatility  
- Seasonal and event-based price fluctuations are evident  

---

## Impact
- Rising food prices negatively affect **food security and nutrition**, especially among low-income households  
- Children and vulnerable populations face increased health risks  
- Insights support evidence-based policymaking for subsidies, imports, and agricultural planning  

---

## Limitations
- Limited real-time data availability  
- Dashboard relies on a static dataset  
- Lack of socio-economic household-level data  
- Seasonal analysis constrained by sample size  

---

## Recommendations
- Strengthen domestic agricultural production  
- Implement real-time food price monitoring systems  
- Use dashboards for early warning and policy intervention  
- Improve supply chain and transportation infrastructure  

---

## Challenges
- Poor data quality and preprocessing complexity  
- Manual data updates  
- Limited dataset size for long-term forecasting  
- Dashboard design for diverse user groups  

---

## Conclusion
This project demonstrates how **data mining and interactive dashboards in R** can transform complex food price data into meaningful insights. The findings highlight structural issues in Sri Lanka’s food pricing system and emphasize the importance of data-driven approaches to address food insecurity and economic instability.

---

## Authors (Group Project)
- **W.M.D. Subhashwaree**  
- **G.G.I. Gamanayake**  
- **J.A.N.I. Jayawardhana**  
- **M.G.K.S.G. Gamage**  

BSc in Applied Data Science Communication (UG)  
General Sir John Kotelawala Defence University  

---

## License
This project is for **educational purposes only**.


