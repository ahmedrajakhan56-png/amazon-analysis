# Amazon Product Profitability Analysis
### *End-to-End Data Analytics Project: Python • AWS • Power BI • SQL*

<div align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white"/>
  <img src="https://img.shields.io/badge/PowerBI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black"/>
  <img src="https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white"/>
  <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white"/>
</div>

<br>

<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=600&size=24&duration=3000&pause=1000&color=FF9900&center=true&vCenter=true&random=false&width=600&lines=%F0%9F%92%B0+%2417.6+Lakhs+Recovery+Potential;%F0%9F%93%89+1%2C465+Products+Analyzed;%F0%9F%8E%AF+140%25+ROI+Identified;%F0%9F%93%8A+3-Page+Interactive+Dashboard" alt="Typing SVG" />
</p>

---

## 📋 Project Overview

An **end-to-end data analytics project** analyzing **1,465 Amazon products** to identify profit/loss patterns, optimize pricing strategy, and provide actionable business recommendations for an Amazon seller facing profitability challenges.

### 🎯 Business Problem
An Amazon seller with **1,465 products** in their catalog was struggling to answer critical questions:

| ❓ Question | 💡 Why It Matters |
|------------|-------------------|
| **Which products are truly profitable?** | 85% profitable but 11% bleeding money |
| **Why are 165 products making losses?** | ₹12.4 Lakhs annual loss bleeding |
| **How to optimize discounts without losing sales?** | Loss products have 72% avg discount |
| **Which segments to focus on for growth?** | Mid-range gives 44% of profit |

---

## 💰 Key Business Impact

<div align="center">

| Metric | Value | Impact |
|--------|-------|--------|
| <span style="font-size:1.2em;">📉 **Loss-Making Products**</span> | **165 (11% of catalog)** | Critical issues identified |
| <span style="font-size:1.2em;">💸 **Annual Loss**</span> | **₹12.4 Lakhs** | Quantified bleeding |
| <span style="font-size:1.2em;">📈 **Recovery Potential**</span> | **₹17.6 Lakhs** | **140% ROI opportunity** |
| <span style="font-size:1.2em;">🎯 **Actionable Strategies**</span> | **4 with timeline** | Ready to implement |

</div>

---

## 🛠️ Tech Stack

<div align="center">

| Category | Technologies Used | Purpose |
|----------|-------------------|---------|
| **Data Processing** | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white) Pandas, NumPy, Matplotlib, Seaborn | Data cleaning & EDA |
| **Cloud Services** | ![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat&logo=amazon-aws&logoColor=white) S3, Athena, IAM | Data lake & serverless querying |
| **Visualization** | ![Power BI](https://img.shields.io/badge/PowerBI-F2C811?style=flat&logo=powerbi&logoColor=black) | 3-Page Interactive Dashboard |
| **Database** | ![AWS Athena](https://img.shields.io/badge/AWS%20Athena-232F3E?style=flat&logo=amazon-aws&logoColor=white) | Serverless SQL queries |
| **Version Control** | ![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white) ![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white) | Code management |

</div>

---

## ☁️ AWS Implementation

### S3 Storage Architecture

```python
# AWS S3 Bucket Configuration
bucket_name = "amazon-profit-6663"
data_size = "4.7 MB"
storage_class = "STANDARD"
encryption = "AES-256"
access = "IAM controlled"

# Cleaned dataset stored and processed
# Integrated with AWS Athena for serverless querying
```

### AWS Services Used
| Service | Purpose | Configuration |
|---------|---------|---------------|
| **Amazon S3** | Data lake storage | `amazon-profit-6663` bucket |
| **AWS Athena** | Serverless SQL queries | Direct query on S3 data |
| **AWS IAM** | Secure access management | Role-based permissions |

---

## 📊 Power BI Dashboard (3-Page Interactive)

---

### 🏆 Page 1: Executive Dashboard

<div align="center">
  <img src="https://github.com/ahmedrajakhan56-png/amazon-analysis/blob/main/Screenshot%202026-02-25%20202047.png?raw=true" alt="Executive Dashboard" width="90%"/>
</div>

<br>

**📌 Key KPIs at a Glance:**

<div align="center">

| KPI | Value | Status |
|-----|-------|--------|
| 📦 **Total Products** | **1,465** | Full catalog analyzed |
| 📊 **Average Margin** | **3.85%** | Industry average |
| 💰 **Total Profit** | **₹0.65 Cr** | Annual profit |
| ✅ **Profitable Products** | **85%** | Healthy portfolio |

</div>

**🎯 Executive Insights:**
- Majority of products (85%) are profitable
- ₹65 Lakhs annual profit generated
- Need to address the 11% loss-making products

---

### 📈 Page 2: Profitability Analysis

<div align="center">
  <img src="https://github.com/ahmedrajakhan56-png/amazon-analysis/blob/main/Screenshot%202026-02-25%20202117.png?raw=true" alt="Profitability Analysis" width="90%"/>
</div>

<br>

**💡 Key Profitability Insights:**

<div align="center">

| Segment | Price Range | Profit Contribution | Key Finding |
|---------|-------------|---------------------|-------------|
| 🎯 **Mid-Range** | **₹500-2000** | **44% of total profit** | Sweet spot! |
| 💎 **Budget** | **< ₹500** | **Up to 60% margins** | High margin potential |
| ⚠️ **Loss Products** | Various | **72% avg discount** | Over-discounting issue |

</div>

**📊 Segment Performance:**
- **Mid-Range (₹500-2000):** 44% profit contribution - **FOCUS HERE**
- **Premium (>₹2000):** 32% profit - Healthy margins
- **Budget (<₹500):** 24% profit but 60% margins possible
- **Loss Products:** 72% average discount - **CRITICAL ISSUE**

---

### 🔍 Page 3: Loss Products Deep Dive

<div align="center">
  <img src="https://github.com/ahmedrajakhan56-png/amazon-analysis/blob/main/Screenshot%202026-02-25%20202136.png?raw=true" alt="Loss Analysis" width="90%"/>
</div>

<br>

**🔬 Why 165 Products Are Losing Money:**

<div align="center">

| Metric | Loss Products | Profitable Products | Difference |
|--------|---------------|---------------------|------------|
| 💰 **Average Price** | **₹445** | **₹2,845** | **6x lower** |
| 🏷️ **Average Discount** | **35%** | **18%** | **2x higher** |
| 📊 **Cost-to-Price Ratio** | **161%** | **82%** | **Selling below cost** |

</div>

**⚠️ Root Causes Identified:**
1. **Over-discounting:** 35% vs 18% - killing margins
2. **Pricing too low:** 6x cheaper than profitable products
3. **Selling below cost:** 161% cost-to-price ratio means every sale loses money
4. **No minimum price threshold:** Products priced too aggressively

---

## 💡 Business Recommendations

### 4 Actionable Strategies with Timeline

<div align="center">

| # | Strategy | Actions | Timeline | Expected Impact |
|---|----------|---------|----------|-----------------|
| **1** | **Price Optimization** | Reprice 165 loss products at cost+20% min | Month 1 | ₹5.2L recovery |
| **2** | **Discount Rationalization** | Cap discounts at 25%, tiered structure | Month 2-3 | ₹4.8L savings |
| **3** | **Mid-Range Focus** | Marketing push on ₹500-2000 segment | Month 3-4 | ₹3.6L growth |
| **4** | **Budget Restructuring** | Bundle low-price products, increase ASP | Month 4-6 | ₹4.0L improvement |

| 💰 **Total Recovery Potential** | **₹17.6 Lakhs** | **140% ROI** |
|---|---|---|

</div>

---

## 📊 Key Metrics Dashboard

<div align="center">

| Metric | Value | Interpretation |
|--------|-------|----------------|
| **Total Revenue** | ₹3.2 Cr | Healthy top line |
| **Total Cost** | ₹2.55 Cr | Manageable COGS |
| **Net Profit** | ₹0.65 Cr | 20.3% margin |
| **Profit Margin** | 20.3% | Above average |
| **Loss-Making Products** | 11.3% | Needs attention |
| **Average Discount** | 24.5% | Can be optimized |

</div>

---

## 📂 Project Structure

```
amazon-analysis/
├── 📁 data/
│   ├── 📁 raw/                 # Original dataset (1,465 products)
│   └── 📁 processed/           # Cleaned data (4.7 MB)
├── 📁 notebooks/
│   ├── 📓 01_eda.ipynb         # Exploratory Data Analysis
│   └── 📓 02_profitability_analysis.ipynb  # Core analysis
├── 📁 sql/
│   └── 📜 athena_queries.sql   # AWS Athena queries
├── 📁 powerbi/
│   └── 📊 dashboard.pbix       # Interactive Power BI dashboard
├── 📁 aws/
│   └── 🐍 s3_setup.py          # S3 bucket configuration
├── 📄 LICENSE
└── 📖 README.md
```

---

## 🚀 Getting Started

### Prerequisites
```bash
# Required installations
Python 3.8+
AWS Account with CLI configured
Power BI Desktop
Git
```

### Quick Start

```bash
# 1. Clone repository
git clone https://github.com/ahmedrajakhan56-png/amazon-analysis.git
cd amazon-analysis

# 2. Install Python dependencies
pip install -r requirements.txt

# 3. Configure AWS
aws configure
# Enter your AWS Access Key ID
# Enter your AWS Secret Access Key
# Enter region (ap-south-1 for Mumbai)

# 4. Run analysis
python src/main.py

# 5. View dashboard
# Open powerbi/dashboard.pbix in Power BI Desktop
```

---

## 🎓 Key Learnings & Achievements

### ✅ Technical Achievements
- **End-to-end pipeline**: Raw CSV → Cleaned data → AWS S3 → Athena → Power BI
- **Cloud integration**: Serverless querying with AWS Athena (₹0 cost for small datasets)
- **Interactive dashboards**: 3-page Power BI with bookmarks and drill-through
- **Python ETL**: Pandas transformations for 1,465 records

### 💼 Business Impact
- **Identified ₹12.4 Lakhs** annual loss root causes
- **Quantified ₹17.6 Lakhs** recovery potential (140% ROI)
- **Segmented products** into actionable categories
- **Provided 4 strategies** with clear timeline

---

## 📊 Dataset Features

| Column | Description | Business Relevance |
|--------|-------------|-------------------|
| `product_id` | Unique identifier | Track individual products |
| `category` | Product category | Segment analysis |
| `price` | Selling price (₹) | Revenue driver |
| `cost` | Product cost (₹) | Margin calculation |
| `discount_percentage` | Applied discount | Profitability impact |
| `margin_percentage` | Profit margin | Performance metric |
| `segment` | Price segment | Strategic grouping |
| `profit_loss_status` | Profitable/Loss | Action flag |

---

## 📈 Visual Insights

<div align="center">

| Dashboard | Key Takeaway |
|-----------|--------------|
| **Executive View** | 85% products profitable, ₹0.65Cr profit |
| **Profitability Analysis** | Mid-range (₹500-2000) gives 44% profit |
| **Loss Analysis** | 2x discounts, 6x lower prices killing margins |

</div>

---

## 🔮 Future Scope

- [ ] **Machine Learning model** to predict product profitability
- [ ] **Real-time dashboard** with live API integration
- [ ] **Automated alerts** when products approach loss threshold
- [ ] **A/B testing framework** for discount optimization
- [ ] **Inventory forecasting** based on profitability

---

## 📄 License

This project is licensed under the **MIT License** - see the [LICENSE](MIT License.txt) file for details.

---

## 🙏 Acknowledgments

- Dataset source: Amazon seller catalog
- Inspiration: Real business problem solving
- Tools: Python community, AWS, Microsoft Power BI

---

## 📬 Connect With Me

<div align="center">
  
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:ahmedrajakhan56@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ahmed-raja-khan)
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/ahmedrajakhan56-png)
[![Portfolio](https://img.shields.io/badge/Portfolio-FF5722?style=for-the-badge&logo=google-chrome&logoColor=white)](https://github.com/ahmedrajakhan56-png)

**Ahmed Raja Khan**  
Data Analyst | Python | AWS | Power BI | SQL

📧 **Email:** [ahmedrajakhan56@gmail.com](mailto:ahmedrajakhan56@gmail.com)  
🔗 **LinkedIn:** [www.linkedin.com/in/ahmed-raja-khan](https://www.linkedin.com/in/ahmed-raja-khan)

</div>

---

<div align="center">
  
### ⭐ If you found this project helpful, please consider giving it a star!

*Last Updated: March 2026*

</div>
```
