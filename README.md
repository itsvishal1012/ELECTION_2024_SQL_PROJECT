# India General Elections 2024 - Data Analysis

This repository contains SQL-based analysis of the **India General
Elections 2024** using official constituency and party-level datasets.
It provides insights into seat distribution, alliance performance (NDA,
I.N.D.I.A., Others), candidate-level statistics, and voting patterns.

------------------------------------------------------------------------

## 📂 Project Structure

-   `statewise_results.csv` → State-wise election results
-   `partywise_results.csv` → Party-wise seats won
-   `constituencywise_results.csv` → Constituency winners with candidate
    & margin
-   `constituencywise_details.csv` → Candidate-level voting data (EVM &
    Postal)
-   `states.csv` → Metadata of states and IDs
-   `SQLQuery1.sql` & `SQLQuery2.sql` → SQL scripts for analysis
-   `SQL Queries.docx` → Documentation of all SQL queries with
    explanations

------------------------------------------------------------------------

## 🗂️ Database Schema

### 1. **states**

Contains state-level information with unique identifiers.

### 2. **statewise_results**

Contains election results mapped to states and constituencies.

### 3. **partywise_results**

Contains party-level results with number of seats won and alliance
classification (NDA, I.N.D.I.A, OTHER).

### 4. **constituencywise_results**

Contains winning candidate details, total votes, and victory margins for
each constituency.

### 5. **constituencywise_details**

Contains detailed candidate-level voting information including EVM and
postal votes.

------------------------------------------------------------------------

## 📊 Key Analysis Areas

-   Total seats in the Lok Sabha
-   Seats available and won in each state
-   Performance of alliances (NDA, I.N.D.I.A., and Others)
-   Party-wise performance within alliances
-   Winning candidate details (party, alliance, margin, votes)
-   Distribution of EVM votes vs Postal votes in each constituency
-   Top candidates by votes in constituencies
-   Runner-up analysis across constituencies
-   State-level metrics: total seats, candidates, parties, and votes

------------------------------------------------------------------------

## 🏆 Features

-   ✅ State-wise & constituency-wise seat analysis
-   ✅ Party & alliance-level seat breakdown (NDA, I.N.D.I.A., Others)
-   ✅ Candidate-level EVM vs Postal votes
-   ✅ Victory margins and runner-up analysis
-   ✅ Insights on total votes, candidates, and parties per state

------------------------------------------------------------------------

## 🚀 How to Use

1.  Clone this repository
2.  Import datasets into SQL Server or PostgreSQL.
3.  Run queries from `SQLQuery1.sql` and `SQLQuery2.sql`.
4.  Explore the results for insights.

------------------------------------------------------------------------

## 📌 Example Insights

-   NDA won the **maximum seats** nationally.
-   Certain states show **regional dominance** by parties (e.g., TDP in
    Andhra Pradesh, DMK in Tamil Nadu).
-   EVM votes strongly outweigh postal votes, but in close contests
    postal votes impacted final outcomes.

------------------------------------------------------------------------

## 👨‍💻 Author
VISHAL SAINI(https://www.linkedin.com/in/vishal-saini-5b4b0b253/)

------------------------------------------------------------------------

## 📜 License

This project is for **educational and research purposes**. Data is based
on publicly available election results.
