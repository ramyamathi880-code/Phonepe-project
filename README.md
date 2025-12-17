📊 PhonePe Pulse Data Visualization Project

📌 Project Overview:
           This project focuses on analyzing and visualizing PhonePe Pulse data using Python, SQL, and Streamlit.  
The original PhonePe data is available in **JSON format**, which is converted into **CSV format** for easier data processing, storage, and visualization.

🗂️ Data Source
  - PhonePe Pulse GitHub Repository
  - Data format: **JSON**
  - Data includes:
  - Transactions
  - Users
  - Insurance
  - State and district-level insights


🔄 JSON to CSV Conversion (Core Concept)
    PhonePe data is originally stored in nested JSON structures.  
To make the data suitable for analysis:

1. JSON files are read using Python
2. Nested data is extracted and flattened
3. Data is converted into Pandas DataFrames
4. DataFrames are saved as CSV files
5. CSV files are loaded into MySQL database

This conversion simplifies querying and visualization.


## 🧱 Project Structure
```
phonepe_pro.py/
│
├── data/
│   ├── json/
│   │   ├── aggregated/
│   │   ├── map/
│   │   └── top/
│   │
│   └── csv/
│       ├── agg_transaction.csv
│       ├── agg_user.csv
│       ├── map_transaction.csv
│       ├── map_user.csv
│       └── top_transaction.csv
│
├── scripts/
│   ├── json_to_csv_aggregated.py
│   ├── json_to_csv_map.py
│   ├── json_to_csv_top.py
│   └── mysql_connection.py
│
├── sql/
│   └── phonepe_db.sql
│
├── scro_01.py
├── requirements.txt
└── README.md
```

🛠️ Technologies Used
       - Python
       - Pandas
       - MySQL
       - Streamlit
       - Plotly

📈 Features:
- State-wise transaction analysis
- District-level insights
- Device brand usage analysis
- Interactive charts using Streamlit
- SQL-based data retrieval

▶️ How to Run the Project:
1. Clone the repository
2. Install required libraries
   ```
   pip install -r requirements.txt
   ```
3. Run Streamlit app
   ```
   streamlit run scro_01.py
   ```

🎯 Key Learning Outcomes
    - Handling large JSON datasets
    - Converting nested JSON to CSV
    - Database integration using MySQL
    - Building interactive dashboards with Streamlit

👩‍💻 Author
Ramya  
PhonePe Pulse Data Visualization Project
