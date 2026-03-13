Crypto API ETL Pipeline
This project is a Python-based ETL (Extract, Transform, Load) script that fetches cryptocurrency market data from the CoinGecko API, processes it, and loads it into a PostgreSQL database. It demonstrates a complete ETL workflow with real-world data.

🚀 Overview
The script performs the following steps:

Extract — Retrieve cryptocurrency data via REST API (CoinGecko).
Transform —
Convert date fields to UTC datetime.
Filter by coin symbols based on user input (* for all).
Drop unnecessary columns.
Validate — Perform basic data quality checks (null/negative values, data freshness).
Load — Write the result into a PostgreSQL database table.
A rotating log file is generated for monitoring and debugging.

🧠 Key Features
REST API data fetching using requests
Data transformation with pandas
Data quality checks
Logging using Python logging with console + file output
PostgreSQL loading via SQLAlchemy
User interaction for filtering and data validation
Basic bash integration potential
🛠️ Tech Stack
Component	Technology
Language	Python 3.x
HTTP Requests	requests
Data Processing	pandas
Database ORM	SQLAlchemy
Database	PostgreSQL
Logging	Python logging
📦 Installation
Clone the repo:
git clone https://github.com/artembabii3-ops/Projekt.git
cd Projekt
