📊 PhonePe Transaction Analytics Project
🧠 Domain

Digital Payments & Financial Analytics

📌 Project Overview

With the rapid growth of digital payment platforms, analyzing transaction data is essential to understand user behavior, spending patterns, and service performance.
This project focuses on extracting, processing, and visualizing PhonePe transaction data to generate actionable business insights.

🎯 Objective
Analyze transaction, user, and insurance data to uncover trends and patterns
Build an interactive dashboard to visualize insights at state, district, and pin code levels


💼 Business Use Cases
Customer Segmentation: Identify user groups based on spending behavior
Fraud Detection: Detect unusual transaction patterns
Geographical Insights: Analyze transactions across states and districts
Payment Performance: Identify popular payment categories
User Engagement: Track activity for retention strategies
Product Development: Improve features using data insights
Insurance Insights: Analyze insurance transactions for better offerings
Marketing Optimization: Target campaigns based on user behavior
Trend Analysis: Understand seasonal and time-based trends
Competitive Benchmarking: Evaluate performance against competitors


🛠️ Tech Stack
Python (Pandas, NumPy, Matplotlib, Seaborn)
SQL (MySQL / PostgreSQL)
Streamlit (Dashboard)
GitHub (Data Source)


🔄 Project Approach
📥 Data Extraction
Cloned PhonePe dataset from GitHub
Loaded raw data into SQL database

🗄️ SQL Database Design

🔹 Aggregated Tables
Aggregated_user – User-related aggregated data
Aggregated_transaction – Transaction summaries
Aggregated_insurance – Insurance data

🔹 Map Tables
Map_user – User mapping data
Map_map – Transaction values by state & district
Map_insurance – Insurance mapping

🔹 Top Tables
Top_user – Top users
Top_map – Top states, districts, pincodes
Top_insurance – Top insurance categories

📊 SQL Analysis
Wrote queries to analyze:
Transaction trends
Regional performance
Top contributors
🐍 Data Analysis (Python)
Used Pandas for data manipulation
Used Matplotlib & Seaborn for visualization
Created charts:
Bar charts
Pie charts
Trend graphs

📈 Dashboard Creation
Built an interactive dashboard using Streamlit
Features:
Real-time filtering
Region-based insights
Category-wise analysis

💡 Insights Generation
Identified high-performing states and districts
Found key transaction trends and user behavior patterns
Analyzed insurance adoption trends

📊 Key Results
Efficient data extraction and integration pipeline
Strong SQL-based analytical skills
Interactive visualizations using Python & Streamlit
Improved analytical and problem-solving capabilities
Clear business insights from large-scale data

🏁 Conclusion

The project successfully transforms raw transaction data into meaningful insights through a structured data pipeline.
It enables better understanding of user behavior, transaction trends, and regional performance.

💼 Business Recommendations
Focus marketing on high-performing regions
Enhance fraud detection using anomaly patterns
Improve user engagement strategies

ptimize payment features based on usage trends

🚀 How to Run the Project
# Clone repository
git clone <repo-link>

# Install dependencies
pip install -r requirements.txt

# Run Streamlit app
streamlit run app.py

📁 Project Structure

project/
│
├── data/
├── sql/
├── welcome.ipynb/
├── app.py
├── requirements.txt
└── README.md


🙌 Author

Abhinand
