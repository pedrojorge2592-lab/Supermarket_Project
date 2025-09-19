# Substitute Products in Case of Stock-Outs  

This project analyzes product substitution behavior in retail settings, focusing on how customers react when certain products are out of stock. By applying association rule mining (Apriori algorithm) and exploratory data analysis, we identify candidate substitutes, visualize brand switching, and provide actionable recommendations for assortment planning.  

---

## 📊 Project Overview  

- **Goal**: Detect substitute products when stock-outs occur.  
- **Method**:  
  - Run Apriori **per subcategory**.  
  - Select subcategories based on **revenue** or **purchase frequency**.  
  - Focus on **rules with lift < 1** → candidate substitutes.  
- **Analysis Includes**:  
  - Data import, cleaning, and preprocessing.  
  - Exploratory Data Analysis (EDA).  
  - Association rule mining (Apriori).  
  - Visualization of brand switching and price differences.  
  - Managerial recommendations.  

---

## 🗂 Data  

- **Sources**: Sales, product, and account info tables.  
- **Processing Steps**:  
  - Merged datasets into a fact table.  
  - Created unit price and unit size columns.  
  - Cleaned missing values.  

---

## 🔍 Methods  

1. **Exploratory Data Analysis (EDA)**  
   - Revenue importance → prioritize high-impact categories.  
   - Brand diversity → identify opportunities for substitution.  
   - Assortment richness → check if substitution is feasible.  
   - Purchase volume → ensure relevance.  

2. **Association Rules (Apriori)**  
   - Applied per subcategory.  
   - Filtered candidate substitutes using **lift < 1**.  

3. **Visualization & Insights**  
   - Substitution dynamics between brands.  
   - Price comparisons between original and substitute products.  

---

## 🛠️ Technologies Used  

- **Python**  
- Jupyter Notebook  
- Libraries:  
  - `pandas`, `numpy` (data processing)  
  - `matplotlib`, `seaborn` (visualization)  
  - `mlxtend` (Apriori algorithm, association rules)  

---

## 🚀 How to Run  

1. Clone the repository:  
   ```bash
   git clone https://github.com/yourusername/Supermarket_Project.git
   cd Supermarket_Project
