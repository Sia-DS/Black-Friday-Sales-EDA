# Black-Friday-Sales-EDA
Exploratory Data Analysis (EDA) on Black Friday Sales Dataset – analyzing customer demographics, purchase behavior, and product insights to identify key spending patterns and actionable business strategies.

## 📌 Project Agenda
The goal of this project is to perform **Exploratory Data Analysis (EDA)** on the Black Friday Sales dataset.  
The dataset contains customer demographics, product categories, and purchase values.  
Through this project, I aim to answer:  
- Which customer segments spend the most?  
- What product categories drive sales?  
- How do demographics like age, gender, and city influence purchase behavior?  

---

## 🔎 Key Observations
- **Gender:** Males spend slightly more than females.  
- **Age:** The **51–55 age group** records the highest average purchases.  
- **Marital Status:** Spending is nearly the same for married and unmarried customers.  
- **Occupation:** Occupation types **0, 4, 7, and 17** show higher average spending.  
- **City Category:** Customers from **City Category B** spend the most on average.  
- **Stay Duration:** Years of stay in the city do **not significantly affect** spending.  
- **Products:** Some products are frequently purchased but low-value, while others have fewer sales but high revenue contribution.  
- **Purchase Distribution:** Right-skewed, with most transactions between ₹5,000–₹15,000 and a few high-value outliers.  

---

## 💡 Value Added by the Project
- Provides insights into **customer segmentation** for targeted marketing.  
- Identifies **high-value products** that drive revenue despite lower sales volume.  
- Highlights the **most profitable demographic group** for sales campaigns.  
- Builds a **foundation for predictive modeling** (recommendation engines, customer profiling).  

---

## 📢 Suggestions
- Focus marketing campaigns on **customers aged 26–55**, especially **males in City Category B**.  
- Prioritize **high-value products** for promotions rather than only high-frequency items.  
- Develop **personalized recommendation systems** based on age, gender, and occupation.  

---

## 🛠 Walkthrough of the Project
1. **Data Cleaning & Preparation**  
   - Handled missing values in product categories.  
   - Verified data types and transformed categorical variables.  

2. **Univariate Analysis**  
   - Explored distributions of gender, age, occupation, city category, and stay duration.  
   - Visualized categorical counts using Seaborn.  

3. **Bivariate Analysis**  
   - Compared average purchase against demographic variables (age, gender, occupation, city, stay years).  
   - Discovered high-value segments like **51–55 age group** and **City B residents**.  

4. **Purchase Distribution**  
   - Analyzed histogram and boxplot to detect skewness and outliers.  

5. **Product Analysis**  
   - Identified top 10 products by **count of sales** and **total purchase value**.  
   - Differentiated between volume-driven and value-driven products.  

6. **Key Takeaways**  
   - Customer behavior insights that can guide **business strategy** and **targeted marketing**.  
   - Provides a base for future **Machine Learning models** (customer segmentation, purchase prediction).  

---

## 🚀 Tech Stack
- **Python** (Pandas, NumPy, Matplotlib, Seaborn)  
- **Jupyter Notebook**  


