# smart-city-utilities-management
A comparative database project using SQL (PostgreSQL), NoSQL (MongoDB), and Blockchain concepts to manage utility billing, usage, and residents for smart cities. Designed for flexibility, integrity, and performance in real-world data infrastructure scenarios.
This project presents a comparative study and implementation of Smart City Utilities Management using three different data architectures: **SQL (Relational Databases)**, **NoSQL (MongoDB)**, and **Blockchain** simulation.


## 🧠 Objective
Design a data-driven solution to manage:
- Residents and their profiles
- Utility types (e.g., electricity, water)
- Utility bills and usage data

Then, implement the system in:
1. **PostgreSQL** (Relational DB)
2. **MongoDB Atlas** (NoSQL Embedded Documents)
3. **Blockchain Simulation** (for audit and security)

---

## 🔢 SQL Implementation

### Tables
- `Residents`
- `Utility_Types`
- `Bills`
- `Utility_Usage`

### Features
- Foreign key relationships
- Complex JOIN queries
- Views for reporting

### Sample Queries
- Monthly usage summary
- Top 5 spenders
- High usage alerts
- View for total bills

---

## 🌐 NoSQL Implementation

- Used **MongoDB Atlas**
- Data modeled using **embedded documents** (residents, bills, usage)
- Sample queries include:
  - Residents with usage > 100
  - Bills for electricity
  - Resident name search

---

## 🔐 Blockchain Simulation

- Implemented a simplified model of block creation
- Chained data using SHA256 hashes
- Simulated consensus process for verification

---

## 📊 Technologies Used

| Technology | Purpose |
|------------|---------|
| PostgreSQL | Structured SQL database |
| MongoDB    | NoSQL document database |
| Python     | ETL, simulation |
| JSON       | Data modeling |
| Blockchain | Data integrity & trust |

---

## 📚 References

- Elmasri & Navathe (2016) - *Fundamentals of Database Systems*  
- Swan (2015) - *Blockchain: Blueprint for a New Economy*

---

## ✅ Key Takeaways

- **SQL** is powerful for logic-heavy, structured systems
- **NoSQL** offers flexibility and ease of scaling
- **Blockchain** boosts data trust & auditability, but needs proper design

---

## 🙌 Special Thanks

Gratitude to **Professor David Sanford** for continuous support, encouragement, and valuable insights throughout the project journey.

---

## 📂 License

This project is intended for educational use only.  
MIT License coming soon.
