# 📊 A/B Testing: Marketing Campaign Performance Analysis

## 🧭 Overview

In the fast-paced world of digital marketing, **data-driven decisions** can be the difference between a missed opportunity and a successful campaign.  
This project explores an A/B test comparing two strategies across **Facebook** and **AdWords**, aiming to uncover which platform drives better user engagement, conversions, and ROI.

Through Python-based analysis, we evaluated key performance metrics, applied hypothesis testing, and visualized insights to guide future marketing strategy.

---

## 🎯 Objectives

- 🔍 **Measure Campaign Effectiveness**  
  Determine whether the **Test** or **Control** group performs better.
  
- 📈 **Track Key Metrics**  
  Focus on **CTR**, **conversion rates**, and **cost-efficiency**.
  
- 🧪 **Validate with Statistics**  
  Use **Z-tests** to confirm statistically significant outcomes.
  
- 🚀 **Drive Optimization**  
  Deliver actionable recommendations for smarter marketing investments.

---

## 💡 Business Impact

- 💰 **Maximize ROI**: Identify platforms that yield better value per dollar spent.  
- 🎯 **Focus Strategy**: Tailor marketing tactics based on platform strengths.  
- 📊 **Data-Driven Decisions**: Empower campaign planning with evidence-backed insights.

---

## 📁 Dataset Overview

| Feature       | Description                                  |
|---------------|----------------------------------------------|
| `Group`       | Indicates Control or Test group              |
| `Impressions` | Number of times the ad was shown             |
| `Clicks`      | Number of clicks received                    |
| `Conversions` | Number of users completing a desired action  |
| `Cost`        | Total cost spent on the campaign             |

---

## 📌 Key Metrics

- **Click-Through Rate (CTR)**: Clicks ÷ Impressions  
- **Conversion Rate**: Conversions ÷ Clicks  
- **Cost Per Click (CPC)**: Cost ÷ Clicks  
- **Cost Per Conversion (CPA)**: Cost ÷ Conversions  

---

## 🔍 Hypotheses

### 📉 Null Hypothesis (H₀)  
> There is **no significant difference** in performance between Facebook and AdWords campaigns.

### 📈 Alternative Hypothesis (H₁)  
> There **is** a significant difference in performance metrics, favoring one platform.

---

## 📊 Results & Insights

### 🚦 1. Engagement

| Platform | CTR (%) | Clicks/Day |
|----------|---------|------------|
| Facebook | **2.20%** | 44.0      |
| AdWords  | 1.30%   | **60.4**   |

🗣️ **Story**: Facebook ads attracted more clicks relative to impressions, signaling higher ad content appeal.  
However, AdWords led in total daily clicks, making it better for visibility.

---

### 💡 2. Conversions

| Platform | Conversion Rate (%) | Conversions/Day |
|----------|----------------------|-----------------|
| Facebook | **27.15%**            | **11.7**        |
| AdWords  | 10.18%               | 6.0             |

📣 **Story**: Facebook not only engaged users—it converted them.  
It doubled AdWords' conversion rate, making it ideal for **action-oriented campaigns**.

---

### 💸 3. Cost Efficiency

| Metric      | Facebook | AdWords |
|-------------|----------|---------|
| CPC         | **$2.18**  | $2.38   |
| CPA         | **Lower**  | Higher  |

💬 **Story**: Facebook wins again with **cheaper clicks and conversions**, driving better ROI for performance-focused advertisers.

---


- Facebook **starts strong** with a high CTR.  
- It **finishes stronger** with an excellent conversion rate.  
- AdWords **generates traffic**, but **struggles converting**.

🧭 **Moral**: For efficiency and conversion, Facebook is the clear hero.

---

## 🔬 Methodology

1. **Data Cleaning**: Removed nulls, handled outliers, formatted columns.
2. **Exploratory Data Analysis (EDA)**:
   - Compared metrics across groups
   - Used bar and box plots for clarity
3. **Hypothesis Testing**:
   - Two-proportion Z-test on conversion rates
4. **Metric Analysis**:
   - Calculated CTR, CPC, CPA for each platform

---

## 🛠 Tools & Technologies

- **Python**  
  - `pandas`, `numpy` for data processing  
  - `matplotlib`, `seaborn` for visualization  
  - `scipy.stats` for statistical testing

---

## ✅ Conclusion & Recommendations

### 📢 Summary

| Metric        | Winner     |
|---------------|------------|
| CTR           | Facebook   |
| Conversion    | Facebook   |
| CPC / CPA     | Facebook   |
| Click Volume  | AdWords    |

### ✅ Recommendations

- 🎯 Use **Facebook** for:
  - ROI-focused campaigns
  - High conversion efficiency
  - Budget-conscious marketing

- 📢 Use **AdWords** for:
  - Traffic generation
  - Brand awareness and reach

🌀 **Balanced Strategy**:  
> Use **AdWords to capture audience reach**, then **Facebook to drive results and conversions**.

---

## 📎 Next Steps

- Expand A/B testing to other channels (Instagram, LinkedIn)
- Analyze segmented performance by user demographics
- Integrate time-of-day or device-specific metrics

---




---



