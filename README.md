# 🔴 Indian Bank Database System – SQL Server

This SQL project simulates a complete banking database system covering Accounts, Products, Regions, Branches, Users, and Transactions.  
It enforces data integrity through constraints, triggers, and views to generate analytical insights and automate business rules.

---

## ⚙️ Tools & Technologies
- Microsoft SQL Server (2016–2022)  
- T-SQL (Scripts, Views, Stored Procedures)  
- Database Normalization & Design  

---

## 🧱 Database Structure
**Tables Created:**  
`ProductMaster`, `RegionMaster`, `BranchMaster`, `AccountMaster`, `TransactionMaster`

**Key Constraints:**  
Primary Keys, Foreign Keys, Unique Keys, Check Constraints for Business Rules.

---

## 🔐 Business Logic via Triggers
- **Cheque Date Validation:** Rejects cheques older than 6 months.  
- **Transaction Limit:** Prevents more than 3 cash withdrawals per day.  
- **High-Value Alert:** Raises error for deposits over ₹50,000.  
- **Minimum Balance Rule:** Ensures ₹1000 minimum balance.  

---

## 📊 Views and Reports
- `trans_amount_wise` – Monthly transaction totals by type.  
- `transactions_view` – Account-wise transaction history.  
- Queries for top customers and branch-level summaries.  

---

## 🏆 Achievement
Delivered a robust database system that supports business integrity, automated audits, and compliance alerts.

---

## 🗂️ File
- `SQL PROJECT QUERIES.sql` – Full schema, triggers, and views  

---

## 👨‍💻 Created By
**Pettem Vamshi**  
📍 Hyderabad, India  |  MSc Data Analytics (UWS)  
📧 pettemvamshi@gmail.com  |  🔗 [LinkedIn](https://linkedin.com/in/pettemvamshi)
