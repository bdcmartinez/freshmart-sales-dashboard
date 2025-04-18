# 📊 FreshMart Analytics – Business Growth & Product Trends

Welcome to the **FreshMart Analytics** dashboard project. This Power BI solution provides a comprehensive view of sales performance, product insights, customer behavior, and payment methods across multiple U.S. regions. The dashboard is designed for business decision-makers to quickly identify opportunities, risks, and growth strategies.


---

# 🧪 Data Generation

This project uses **simulated data** to reflect realistic sales behavior across various U.S. regions, customer types, and product categories. The dataset was created with Python using `pandas`, `numpy`, and `Faker`.

### ⚙️ Data Generation Logic (Python)

```python
# Libraries and setup
fake = Faker()
np.random.seed(42)
random.seed(42)

# Parameters
num_customers = 19440
num_days = 1800
start_date = datetime(2024, 10, 1)

# Regions with different sales weights
regions = {
    "California": 1.3,
    "Texas": 1.2,
    "New York": 1.0,
    "Florida": 1.1,
    "Wisconsin": 0.8,
    "Colorado": 0.6,
    "Alabama": 0.5
}

# Payment methods and product categories
payment_methods = ["Cash", "Credit Card", "Debit Card", "Mobile App"]
categories = { ... }  # see full script in repo


```


---

## 📌 Key Features

- **Executive KPIs**  
  Total Revenue, Monthly Growth, Average Ticket, and Transaction Volume.

- **Top Products Analysis**  
  Identify the highest-revenue products and monitor category performance.

- **Customer Segmentation**  
  Classifies customers as New, Regular, or Frequent, helping with loyalty strategy and targeting.

- **Regional Performance**  
  Sales distribution across key states (e.g., Texas and California), with visual maps and state comparisons.

- **Payment Method Analysis**  
  Understand customer preferences in transaction types (Cash, Credit Card, Mobile App, etc.)

- **Performance vs Goals**  
  Revenue and growth metrics are compared against monthly targets to highlight gaps or successes.

---


## 📷 Dashboard Preview

![Dashboard Screenshot](/images/FreshMartAnalytics_page-0001.jpg)

![Dashboard Screenshot](/images/FreshMartAnalytics_page-0002.jpg)

![Dashboard Screenshot](/images/FreshMartAnalytics_page-0002.jpg)




## 📈 Key Insights (From the Dashboard)

- 🥇 **Orange Soda** is the top-selling product by revenue.
- 💸 **Mobile App payments** are underutilized, representing only 12.09% of sales.
- 📍 **Texas and California** generate nearly 40% of all revenue.
- 👥 **Frequent customers** contribute over 60% of total revenue.
- 📉 **Monthly revenue** dropped by 85.31% vs the target — suggesting seasonality or marketing challenges.

---

## ✅ Strategic Recommendations

- 🎁 **Launch a Loyalty Program** for Frequent customers to increase retention.
- 📱 **Promote Mobile Payments** through in-app promotions or discounts.
- 📦 **Optimize Stock** for high-performing products (e.g., Orange Soda, Tuna Can).
- 📈 **Investigate Revenue Drop** with a root cause analysis (price, seasonality, marketing).
- 🗺️ **Leverage High-Performing Regions** by replicating successful bundles in lower-performing states.




## 📬 Contact

For questions, feel free to reach out via GitHub or [bdcmartinez.com](https://bdcmartinez.com)


*This project is for educational and professional portfolio purposes only. All data is simulated.*
