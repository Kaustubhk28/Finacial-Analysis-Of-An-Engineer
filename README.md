# 📈 Financial Analysis of an Engineer  

## 🏆 Objective  
New graduates often struggle to manage their finances while transitioning into professional careers. Making informed financial decisions early on can significantly impact long-term stability and success.  

This project was a collaborative effort by a six-member team, leveraging knowledge from an *Engineering Economic Decision-Making* course to simulate financial planning for a hypothetical software engineer, Rehan Ahmed. The goal was to analyze the financial implications of pursuing different educational paths, settling in two major U.S. tech hubs, and adopting various investment strategies to determine an optimal approach for securing financial stability and building wealth.  

---

## ✨ Project Overview  

### Scenario  
Rehan Ahmed, a recent engineering graduate with an interest in Software Engineering, is evaluating:  
1. Pursuing either a **bachelor’s degree** or a **bachelor’s + master’s degree**.  
2. Living in **Boston, MA** (East Coast) or **Los Angeles, CA** (West Coast), both IT hubs with differing living costs.  
3. Stock investment strategies: **No Stocks**, **Low-Yield Stocks (6%)**, or **High-Yield Stocks (12%)**.  

The project aimed to compute the **future worth (FW)** of these options, factoring in variables like base salary, cost of education, living expenses, transportation, retirement contributions, taxes, and investment returns.

---

## 🗂️ Alternatives  
The analysis compared **12 scenarios**, combining education level, location, and stock investment strategy:  
1. Boston, MA – Bachelor’s – No Stocks.  
2. Boston, MA – Bachelor’s – Low-Yield Stocks.  
3. Boston, MA – Bachelor’s – High-Yield Stocks.  
4. Boston, MA – Bachelor’s + Master’s – No Stocks.  
5. Boston, MA – Bachelor’s + Master’s – Low-Yield Stocks.  
6. Boston, MA – Bachelor’s + Master’s – High-Yield Stocks.  
7. Los Angeles, CA – Bachelor’s – No Stocks.  
8. Los Angeles, CA – Bachelor’s – Low-Yield Stocks.  
9. Los Angeles, CA – Bachelor’s – High-Yield Stocks.  
10. Los Angeles, CA – Bachelor’s + Master’s – No Stocks.  
11. Los Angeles, CA – Bachelor’s + Master’s – Low-Yield Stocks.  
12. Los Angeles, CA – Bachelor’s + Master’s – High-Yield Stocks.  

---

## 📊 Results and Recommendations  

### 1. **Stock Investment Scenarios**  
- **Low-Yield Stocks (6%)** and **High-Yield Stocks (12%)** were evaluated using historical data.  
- Key Findings:  
  - **MARR 0%-6%:** FW order: *No Stocks < Low-Yield Stocks < High-Yield Stocks*.  
  - **MARR 6%-12%:** FW order: *Low-Yield Stocks < No Stocks < High-Yield Stocks*.  
  - **MARR 12%-20%:** FW order: *Low-Yield Stocks < High-Yield Stocks < No Stocks*.  

---

### 2. **Boston vs. Los Angeles (Master’s Degree + Stock Investments)**  
- **MARR ≤ 7%:** LA offers higher FW due to higher salaries, enabling larger investments early on.  
- **MARR ≥ 8%-9%:** Boston becomes the preferred location due to lower living costs, resulting in better net savings.  
- **Key Insight:** While LA provides short-term advantages, Boston is better for long-term financial growth at higher MARR values.  

---

### 3. **Bachelor’s vs. Master’s Degree Scenarios**  
- **MARR ≤ 15%-17%:** A master’s degree offers better FW due to higher earning potential.  
- **MARR ≥ 15%-17%:** A bachelor’s degree becomes advantageous as Rehan begins earning earlier, leading to greater compounded savings over time.  
- **Key Insight:** Higher education is beneficial at lower MARR, but early workforce entry offers better returns at higher MARR.  

---

## 🔑 Decision Variables  
The analysis incorporated the following key variables:  
- **Base Salary and Signing Bonus**  
- **Cost of Education (Bachelor’s vs. Master’s)**  
- **Living Costs (Boston vs. LA)**  
- **Transportation Expenses (Public Transport vs. First/Second Car)**  
- **Investment Returns (No Stocks, Low-Yield, High-Yield)**  
- **Retirement Contributions (Employer Matching)**  
- **Salary Growth Rates**  
- **Taxes, Insurance (Car, House, Medical)**  
- **Food and Leisure Expenses**  

---

## 🌟 Insights and Recommendations  
1. **Investment Strategy:** High-yield stocks maximize FW across most MARR values, except at higher rates where conservative strategies may perform better.  
2. **City Selection:** LA is ideal for short-term financial goals (lower MARR), but Boston excels in long-term financial stability (higher MARR).  
3. **Education Path:** Pursuing a master’s degree offers significant advantages for lower MARR scenarios, while stopping at a bachelor’s degree provides better returns for higher MARR.  

---

## 🚧 Challenges and Limitations  
- Assumed consistent stock returns (6% and 12%) based on historical data.  
- Variability in cost-of-living adjustments across cities.  
- Ignored potential fluctuations in salary growth and market conditions.  
- Educational costs vary widely based on institutions and programs.  

---

## 📚 Figures and Tables  
- **Table 1:** Stock Investment FW Transitions by MARR.  
- **Table 2:** City FW Transitions (Boston vs. LA).  
- **Table 3:** Degree FW Transitions (Bachelor’s vs. Master’s).  
- **Figure 1:** Career Start Timeline and Savings Impact.  

---

## 👥 Team Members  
- Sachin Gahane  
- Kaustubh Khedekar  
- Rehan Ahmed  
- Rahul Kotikalapudi
- Simran Bhatia
- Saksham Saxena

---

## 💡 Conclusion  
This project showcases how sound financial planning and economic decision-making can help young professionals like Rehan navigate major life decisions. By leveraging engineering economics principles, the analysis provides actionable insights for optimizing education, location, and investment choices to achieve long-term financial stability.  
