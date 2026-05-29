🛒 E-Commerce Sales Analysis & Power BI Dashboard
Show Image Show Image Show Image Show Image
📌 Overview
End-to-end exploratory data analysis of 9,800+ Superstore orders using Python and Power BI, uncovering sales trends, regional performance, and customer behavior patterns.

📂 Table of Contents

Case Study
Dataset Description
Tech Stack
Data Cleaning
Data Analysis & Insights
Dashboard
Key Findings


📋 Case Study
Analyzed real-world e-commerce sales data to identify top-performing categories, regions, products, and seasonal trends to support data-driven business decisions.

📊 Dataset Description
ColumnDescriptionOrder IDUnique order identifierOrder DateDate of order placementShip ModeShipping method usedSegmentCustomer segmentRegionGeographic regionCategoryProduct categorySub-CategoryProduct sub-categoryProduct NameName of productSalesRevenue generated
Total Records: 9,800+ orders | Period: 2015–2018

🛠️ Tech Stack
ToolPurposePython 3.13Core programmingPandasData manipulationNumPyNumerical computationMatplotlibData visualizationSeabornStatistical visualizationJupyter NotebookDevelopment environmentPower BIInteractive dashboardGitHubVersion control

🧹 Data Cleaning

Loaded dataset using pd.read_csv() with encoding='latin1'
Verified missing values — zero missing values found ✅
Converted date columns using pd.to_datetime() with dayfirst=True
Extracted Order Month and Order Year for time-series analysis


🔍 Data Analysis & Insights
📦 Category Analysis

Technology — highest revenue ~$830K
Furniture — second ~$730K
Office Supplies — third ~$700K

🌍 Regional Analysis

West — top region ~$710K
East — second ~$669K
South — lowest ~$389K — growth opportunity!

📅 Monthly Trend

November–December — peak sales every year
January–February — lowest sales period
Clear Q4 seasonality pattern identified

🏆 Top Products

Canon imageCLASS 2200 Copier — #1 product ~$60K
Most top products from Technology category

👥 Customer Segment

Consumer — 50.8% of total revenue
Corporate — 30.4%
Home Office — 18.8%

🚚 Ship Mode

Standard Class — most preferred shipping
Same Day — least used — premium pricing

📈 Yearly Growth

2015: $480K → 2018: $722K
50% revenue growth in 4 years!


📊 Power BI Dashboard
VisualChart TypeTotal Sales KPICardCategory SalesBar ChartRegion PerformanceBar ChartMonthly TrendLine ChartCustomer SegmentPie ChartYearly GrowthBar ChartSub-Category SalesBar ChartShip Mode AnalysisBar Chart

💡 Key Findings
✅ Technology category generated highest revenue (~$830K)
✅ West region is top performer — focus market
✅ Q4 (Nov-Dec) shows consistent sales spike — festive season impact
✅ Consumer segment contributes 50%+ revenue
✅ Business grew 50% from 2015 to 2018
✅ Canon Copier — single highest selling product

🚀 Installation & Usage
Step 1 — Clone repository
bashgit clone https://github.com/yashghormade/ecommerce-analysis.git
Step 2 — Install libraries
bashpip install pandas numpy matplotlib seaborn
Step 3 — Run notebook
Open sample.ipynb in Jupyter Notebook and run all cells!

📌 Conclusion
This project demonstrates end-to-end data analysis skills — from raw data cleaning to interactive Power BI dashboard — generating actionable business insights from e-commerce sales data.

👨‍💻 Author
Yash Ghormade
🎓 AIML Engineer | 📊 Aspiring Data Analyst | 💼 Open to Internships
🔗 GitHub | 💼 LinkedIn
