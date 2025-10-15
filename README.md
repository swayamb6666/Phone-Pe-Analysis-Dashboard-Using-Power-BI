# 📊 PhonePe Transaction Analysis Dashboard

A comprehensive Power BI dashboard analyzing PhonePe payment transactions across multiple service categories with interactive visualizations and detailed insights into payment patterns, failures, and financial trends.

![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Status](https://img.shields.io/badge/Status-Complete-success?style=for-the-badge)

## 🗂️ Dataset

The dataset used in this Power BI project is hosted on Google Drive due to GitHub’s file size limit.

📂 **File:** Phonepe-Final-Dataset.xlsx  
📥 [Download Dataset from Google Drive][https://docs.google.com/spreadsheets/d/1bXthUHgFt1veh1AgHnxJd_7Nyyb2he3_/edit?usp=sharing&ouid=116391761430584863718&rtpof=true&sd=true]


## 📄 Quick Access

> **📥 [View Dashboard PDF](phonepe_analysis_dashboard.pdf)** 

---

## 🎯 Project Overview

This Power BI dashboard provides comprehensive analysis of PhonePe transaction data from **January 1, 2024 to December 30, 2024**. The dashboard features **5 interactive tabs**, each dedicated to analyzing different service categories with multiple visualization types including bar charts, pie charts, line graphs, and KPI cards.

### 📅 Analysis Period
**January 1, 2024 - December 30, 2024**

---

## 📈 Key Performance Metrics

### Overall Performance
- **💰 Total Transaction Amount**: ₹3,333M (3.33 Billion)
- **📊 Total Transactions**: 288,000
- **✅ Success Rate**: ~96% across all services
- **❌ Failed Transactions**: ~4% average

### Service-wise Breakdown
| Service | Total Amount | Primary Transaction Volume |
|---------|-------------|---------------------------|
| 💼 **Loans** | ₹2,431M | 50,000 transactions |
| 🛡️ **Insurance** | ₹512.92M | 50,000 transactions |
| 💸 **Money Transfer** | ₹378M | 150,000 transactions |
| 📱 **Recharge & Bills** | ₹51M | 50,000 transactions |

---

## 🖼️ Dashboard Tabs & Features

### **Tab 1: Overview Dashboard** 📊
**Purpose**: High-level summary of all transactions across services

**Key Visualizations**:
- 📅 **Date Range Slicer**: Interactive filter (1/1/2024 - 12/30/2024)
- 🎯 **KPI Cards**: 
  - Total Amount: ₹3,333M
  - Total Transactions: 288K
  - Service-specific transactions: 300K and 12K
- 📊 **Services vs Amount (Horizontal Bar Chart)**:
  - Loans: ₹102M
  - Insurance: ₹22M
  - Money Transfer: ₹15M
  - Recharge & Bills: ₹2M
- 🥧 **Failed Payment Reason (Pie Chart)**:
  - Server error: 33.76% (4.05K)
  - Wrong PIN: 27.61% (3.32K)
  - Insufficient amount: 27% (3.3K)
  - Wrong Info: 5.83% (0.7K)
  - Bank Denied: Small percentage
- 📈 **Monthly Amount Trend (Line Chart)**: 
  - Peaks in April (₹13.7M) and July (₹13.1M)
  - Lowest in January (₹10.8M)

---

### **Tab 2: Insurance Analysis** 🛡️
**Purpose**: Deep dive into insurance product transactions

**Key Metrics**:
- 💰 Total Amount: ₹512.92M
- ✅ Success Rate: 95.75% (47.88K transactions)
- ❌ Failed: 4.25% (2.12K transactions)

**Visualizations**:
- 📅 **Date Range Filter**: Same period selector
- 🥧 **Failed Payment Reasons**:
  - Wrong PIN: 33.66% (715 failures)
  - Server error: 32.58% (717 failures)
  - Insufficient amount: 692 failures
- 📈 **Date vs Amount (Line Chart)**: Monthly trend showing March peak at ₹2.12M
- 🔢 **Insurance Type Performance**:
  - Bike: ₹128.10M total (5.9M amount)
  - Car: ₹129.35M total (5.7M amount)
  - Term Life: ₹128.86M total (5.5M amount)
  - Health: ₹126.61M total (5.1M amount)
- 🟢 **Payment Status (Donut Chart)**: Visual split of successful vs failed

---

### **Tab 3: Loans Analysis** 💼
**Purpose**: Loan transaction patterns and performance

**Key Metrics**:
- 💰 Total Amount: ₹2,431M (Highest revenue service)
- ✅ Success Rate: 95.95% (47.97K transactions)
- ❌ Failed: 4.05% (2.03K transactions)

**Visualizations**:
- 📅 **Interactive Date Filter**
- 🥧 **Payment Failure Analysis**:
  - Wrong Info: 34.53% (700 failures)
  - Server error: 34.14% (692 failures)
  - Bank Denied: 31.33% (635 failures)
- 📈 **Monthly Trend (Line Chart)**:
  - Peak months: February (₹9.2M), March (₹10.3M), August (₹9.6M)
  - Consistent performance throughout year
- 💳 **Loan Type Distribution**:
  - Gold Loan: ₹1,255M total (27M amount)
  - Auto Loan: ₹632M total (26M amount)
  - Mutual Funds: ₹644M total (26M amount)
  - Credit Score: ₹634M total (23M amount)
- 🟢 **Payment Status Visualization**

---

### **Tab 4: Money Transfer Analysis** 💸
**Purpose**: Money transfer patterns across different transfer types

**Key Metrics**:
- 💰 Total Amount: ₹378M
- ✅ Success Rate: 95.98% (143.96K transactions)
- ❌ Failed: 4.02% (6.04K transactions)

**Visualizations**:
- 📅 **Date Range Slicer**
- 🥧 **Failure Reason Distribution**:
  - Insufficient amount: 34.44% (2.08K)
  - Server error: 33.15% (2K)
  - Wrong PIN: 32.42% (1.96K)
- 📊 **Transfer Type Breakdown (Horizontal Bar Chart)**:
  - To UPI ID: ₹95M
  - To Self Account: ₹94M
  - To QR Code: ₹94M
  - To Mobile Number: ₹94M
- 📈 **Monthly Performance (Line Chart)**:
  - Range: ₹29.83M (April) to ₹32.49M (March)
  - Consistent performance with minor fluctuations
- 🟢 **Success vs Failed Status Chart**

---

### **Tab 5: Recharge & Bills Analysis** 📱
**Purpose**: Utility payments and recharge transactions

**Key Metrics**:
- 💰 Total Amount: ₹51M
- 🔢 Total Transactions: 12,815K (Highest transaction count!)
- ✅ Success Rate: 96.16% (48.08K transactions)
- ❌ Failed: 3.84% (1.92K transactions)

**Visualizations**:
- 📅 **Date Filter Control**
- 📈 **Monthly Trend (Line Chart)**:
  - Stable trend between ₹4.1M - ₹4.36M
  - Peak in March (₹4.36M) and May (₹4.35M)
- 🔌 **Bill Type Distribution**:
  - Electricity: 12,815K transactions (₹12.82M)
  - DTH: 12,636K transactions (₹12.64M)
  - Mobile: 12,631K transactions (₹12.63M)
  - Cable TV: 12,613K transactions (₹12.61M)
- 🥧 **Payment Failure Reasons**:
  - Server error: 34.41% (661)
  - Wrong PIN: 33.42% (642)
  - Insufficient amount: 32.17% (618)
- 🟢 **Payment Status (Donut Chart)**

---

## 🎨 Visualizations Used

| Visualization Type | Count | Purpose |
|-------------------|-------|---------|
| 📊 **Bar Charts** | 5 | Service comparison, Transfer types, Category breakdown |
| 🥧 **Pie/Donut Charts** | 10+ | Payment status, Failure reasons distribution |
| 📈 **Line Charts** | 5 | Monthly trends, Time-series analysis |
| 🎯 **KPI Cards** | 10+ | Key metrics display (Amount, Transactions, Success rate) |
| 🎚️ **Slicers** | 5 | Date range filtering across all tabs |
| 🔢 **Tables** | 4 | Detailed category breakdowns |

---

## 🔍 Key Insights Discovered

### 💡 Business Insights

1. **Revenue Distribution**:
   - Loans generate **73% of total revenue** (₹2,431M)
   - Insurance is second with **15% share** (₹512.92M)
   - Small-ticket items (Recharge & Bills) have **highest transaction volume**

2. **Payment Failure Patterns**:
   - **Consistent failure rate**: ~4% across all services
   - **Top 3 reasons** account for 95%+ of failures:
     - Server errors (~34%)
     - Wrong PIN (~33%)
     - Insufficient funds (~32%)
   - Technical issues (server errors) require immediate attention

3. **Seasonal Trends**:
   - **Peak months**: March-April and July-August
   - **Lower activity**: January and September
   - Potential correlation with salary cycles and festivals

4. **Service-Specific Findings**:
   - **Insurance**: Term Life and Car insurance have highest transaction volumes
   - **Loans**: Gold Loans dominate with ₹1,255M total transactions
   - **Money Transfer**: Even distribution across all transfer methods
   - **Recharge & Bills**: Electricity bills generate most activity

---

## 🛠️ Tools & Technologies

- **Power BI Desktop** - Dashboard development and design
- **DAX (Data Analysis Expressions)** - Custom calculations and measures
- **Power Query** - Data transformation and cleaning
- **Data Modeling** - Star schema implementation
- **Interactive Filters** - Date slicers and cross-filtering

---

## 💻 Installation & Usage

### 📄 Quick View (No Installation)
**[Download PDF](phonepe_analysis_dashboard.pdf)** - View all 5 tabs instantly without any software

### 💻 Interactive Experience

#### Prerequisites
- Power BI Desktop (Latest version)
- Windows 10 or later / Mac with Parallels

#### Steps
1. Clone this repository:
   ```bash
   git clone [https://github.com/swayamb6666/Phone-Pe-Analysis-Dashboard-Using-Power-BI.git]
   ```
2. Open `PhonePe_Dashboard.pbix` in Power BI Desktop
3. Explore the 5 interactive tabs
4. Use date slicers to filter data dynamically
5. Hover over visuals for detailed tooltips

---

## 🎓 Skills Demonstrated

✅ **Data Visualization**: 5 different chart types strategically used  
✅ **Dashboard Design**: Clean, intuitive layout with consistent color scheme  
✅ **DAX Proficiency**: Complex calculations and measures  
✅ **Business Intelligence**: Actionable insights from data  
✅ **User Experience**: Interactive filters and drill-through capabilities  
✅ **Data Analysis**: Pattern recognition and trend identification  
✅ **Storytelling**: Data presented in logical, narrative flow  

---

## 🚀 Future Enhancements

- [ ] Add year-over-year comparison
- [ ] Implement predictive analytics for transaction forecasting
- [ ] Create drill-through pages for detailed transaction views
- [ ] Add geographic analysis if location data available
- [ ] Develop mobile-optimized dashboard layout
- [ ] Include customer segmentation analysis
- [ ] Real-time data refresh integration

---

## 📸 Screenshots

*Screenshots of individual tabs can be added here*

---

## 👤 Author

**Your Name**  
📧 Email: swayambana132@gmail.com
💼 LinkedIn: [Swayam Bana](https://www.linkedin.com/in/swayam-bana-394a20293/)  
🐙 GitHub: [@Swayam Bana](https://github.com/swayamb6666)

---

## 🙏 Acknowledgments

- Dataset: PhonePe transaction data (January - December 2024)
- Inspiration: Real-world fintech analytics and payment industry insights
- Tools: Microsoft Power BI Desktop

---

## 📞 Contact & Feedback

Found this project helpful? Feel free to:
- ⭐ **Star this repository**
- 🍴 **Fork it** for your own projects
- 💬 **Open an issue** for questions or suggestions
- 📧 **Email me** for collaboration opportunities

---

**Last Updated**: October 2025  
**Dashboard Version**: 1.0  
**Data Period**: January 1, 2024 - December 30, 2024
