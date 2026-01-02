\# 🧾Retail \& Warehouse Sales Analysis 📊



---

*Analyzing Retail and Warehouse Sales to support data-driven business decisions using Python and Power BI*



---



\## 📌 Overview



This project performs an end-to-end sales analysis on \*\*Retail and Warehouse sales data\*\* using \*\*Python for data analysis\*\* and \*\*Power BI for dashboarding\*\*. The objective is to uncover sales trends, seasonality, top-performing products, suppliers, and key business drivers to support data-driven decision-making.



---



\## 🎯 Business Problem



Effective inventory and sales management are critical in the retail sector. This project aims to:

\* Analyze overall sales performance over time

\* Identify seasonal patterns and demand fluctuations

\* Determine top-performing items, item categories, and suppliers

\* Compare Retail vs Warehouse sales behavior

\* Provide actionable insights for inventory, supplier, and sales strategy optimization



---



\## 📂 Dataset



\*\*Dataset Name:\*\* Retail\_and\_Warehouse\_Sales

\*\*Format:\*\* CSV



\### 📑 Dataset Schema



| Column Name      | Description                              |

| ---------------- | ---------------------------------------- |

| YEAR             | Year of the sales record                 |

| MONTH            | Month of the sales record                |

| SUPPLIER         | Supplier name or identifier              |

| ITEM CODE        | Unique identifier for each product       |

| ITEM DESCRIPTION | Description of the product               |

| ITEM TYPE        | Product category or type                 |

| RETAIL SALES     | Sales made through retail outlets        |

| RETAIL TRANSFERS | Product transfers between retail outlets |

| WAREHOUSE SALES  | Sales from warehouse distribution        |



---



\## 🧰 Tools \& Technologies



\* \*\*Python\*\*: Pandas, NumPy, Matplotlib, Seaborn

\* \*\*Jupyter Notebook\*\*: Data cleaning, EDA, and visual analysis

\* \*\*Power BI\*\*: Interactive dashboard creation

\* \*\*GitHub\*\*: Version control and project documentation



---



\## 📁 Project Structure



```
Retail\_and\_Warehouse\_Sales/

├── README.md

├── requirements.txt

├── data/

│   ├── final\_sales\_dataset\_for\_powerbi.xlsx

│   └── Retail\_and\_warehouse\_Sale.xlsx

├── notebooks/

│   ├── Python\_Project.ipynb

│   └── Code\_HTML\_File.html

├── Dashboard/

│   └── Dashboard.pbix

└── images/

&nbsp;   └── dashboard.png
```



---



\## Data Cleaning \& Preparation



\* Cleaned and standardized date, numeric, and categorical fields

\* Created derived columns (Year-Month, Season, Total Sales)

\* Validated missing values and corrected data inconsistencies



---



\## 🔍 Exploratory Data Analysis (EDA)



EDA was conducted to understand the structure and quality of the dataset and uncover meaningful sales patterns. The analysis focused on:



\* Sales trends over time

\* Seasonal sales distribution

\* Item-wise and category-wise performance

\* Supplier contribution analysis



This helped identify periods of growth and decline, sales concentration risks, and demand variability.



---



\## 📈 Key Analysis \& Visualizations



\### 1️⃣ Sales Trend Over Time



\* Monthly sales trends were analyzed to evaluate sales stability and growth patterns.

\* Identified peak and low-performing periods.



\### 2️⃣ Season-wise Sales Analysis



\* Compared total sales across seasons.

\* Observed strong seasonality with Rainy and Winter seasons contributing the majority of sales.



\### 3️⃣ Item Type \& SKU Analysis



\* Identified top-performing item categories (Beer, Wine, Liquor).

\* Analyzed Top 10 SKUs contributing maximum revenue.



\### 4️⃣ Supplier Performance Analysis



\* Ranked Top 10 suppliers by total sales.

\* Highlighted revenue concentration among a few key suppliers.



---



\## 📊 Power BI Dashboard



An interactive Power BI dashboard was created to visualize insights effectively:



\* Sales trend analysis

\* Season-wise sales distribution

\* Item type and SKU performance

\* Supplier-wise contribution

\* Retail vs Warehouse comparison



!\[Power BI Dashboard](images/dashboard.png)



---



\## ▶️ How to Run This Project



Follow the steps below to run and explore this project locally:



1\. \*\*Clone the repository\*\*



   ```bash

   git clone <repository-url>

   cd Retail-Warehouse-Sales-Analysis

   ```



2\. \*\*Install required dependencies\*\*



   ```bash

   pip install -r requirements.txt

   ```



3\. \*\*Run the Python analysis\*\*



   \* Open 'Python\_Project.ipynb' in \*\*Jupyter Notebook\*\* or \*\*JupyterLab\*\*

   \* Open 'Code\_HTML\_File.html' directly in a browser to view the analysis output



4\. \*\*View the Power BI Dashboard\*\*



   \* Open `Dashboard.pbix` in \*\*Power BI Desktop\*\*

   \* Refresh the data source if required



---



\## 📦 Requirements



The following Python libraries are required to run the analysis:



```

pandas

numpy

matplotlib

seaborn

jupyter

```



\*(You can install all dependencies at once using the `requirements.txt` file.)\*



---



\## 💡 Key Business Insights



\* Sales are highly seasonal, with Rainy season contributing nearly half of total revenue.

\* Beer is the dominant product category, indicating revenue concentration risk.

\* A small number of suppliers and SKUs contribute a large share of sales.

\* Sales show noticeable volatility across months, impacting forecasting accuracy.



---



\## ✅ Business Recommendations



\* Strengthen inventory and supplier planning during peak seasons.

\* Reduce dependency on a few SKUs and suppliers by promoting mid-tier products.

\* Use seasonal insights to optimize marketing and promotional strategies.

\* Improve demand forecasting to reduce sales volatility.



---



\## 👤 Author \& Contact



\*\*Rohan Verma\*\*

Data Analyst | Python | SQL | Power BI | Tableau | Excel



\* 📧 Email: \*vermarohan92571@gmail.com\*

\* 💼 [LinkedIn](https://www.linkedin.com/in/rohan-verma-2011291ab/)



---

