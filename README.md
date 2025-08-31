# India General Elections Result Analysis 2024 (SQL Project)

## 📌 Project Overview
This project analyzes the **2024 Indian General Election results** using **SQL**. It explores seat distribution, alliance performance, candidate details, and voting patterns across constituencies and states. The analysis provides insights into the performance of major political alliances such as **NDA**, **I.N.D.I.A.**, and **OTHER** parties.  

The goal is to demonstrate how SQL can be leveraged to handle large election datasets, extract KPIs, and generate meaningful insights for political analysis.

---

## 🗂️ Project Structure
- **Seat Analysis**
  - Total number of seats in India  
  - Seats available in each state  
  - Seats won by NDA, I.N.D.I.A., and OTHER alliances  

- **Party & Alliance Performance**
  - Seats won by NDA alliance parties  
  - Seats won by I.N.D.I.A. alliance parties  
  - Comparison of seats won by NDA vs I.N.D.I.A. vs OTHER  

- **Candidate-Level Analysis**
  - Winning candidate details (party, alliance, votes, margin of victory)  
  - Top candidates by **EVM votes** (Top 10)  
  - Winners and runners-up in each constituency  

- **State-Level Insights**
  - Seats won by each party in a state (e.g., Andhra Pradesh, Maharashtra, Uttar Pradesh)  
  - Breakdown of votes (EVM vs postal) per state  
  - Alliance-wise seat share across states  

- **Advanced Queries**
  - Added a new column `party_alliance` to classify parties as NDA, I.N.D.I.A., or OTHER  
  - Ranked candidates using SQL window functions (ROW_NUMBER)  
  - Aggregated votes and margins for detailed insights  

---

## ⚙️ Technologies Used
- **SQL** for queries and analysis  
- Compatible with MySQL, SQL Server, or PostgreSQL  

---

## 🚀 How to Use
1. Import the election dataset into your SQL environment.  
2. Run the queries in sequence:  
   - Start with seat analysis  
   - Proceed to alliance and candidate-level insights  
   - Explore state-level breakdowns  
3. Use queries to compare alliances, parties, and candidate performance.  

---

## 📊 Key Insights
- NDA and I.N.D.I.A. alliances dominate most states, with varying strongholds.  
- Candidate-level analysis shows margins of victory and vote shares across constituencies.  
- State-wise breakdown highlights regional party strengths.  
- EVM vs postal vote analysis gives a granular look at voting patterns.  

---

## 📝 Author
Developed by **Suyash Shewale**  
A SQL-based data analysis project to study election outcomes and uncover political insights.
