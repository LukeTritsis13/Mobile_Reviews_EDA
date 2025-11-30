# 📱 Mobile Reviews Data Analysis  
*A Python + Pandas Exploratory Data Analysis Project*

---

## 📌 Project Overview  
This project analyzes mobile phone reviews from multiple brands:  
**Apple, Samsung, Motorola, Realme, Xiaomi, Google, OnePlus**.

The goal is to explore:

- How users rate phones across different brands  
- Differences in camera, battery, display, and performance ratings  
- How price relates to user satisfaction  
- Sentiment distribution across brands  
- Whether users show bias toward certain countries of origin  

This project demonstrates skills in:  
**Python, Pandas, NumPy, Matplotlib, Seaborn, Data Cleaning, EDA, Insight Communication**.

---

## 📁 Dataset - (https://github.com/LukeTritsis13/Mobile_Reviews_EDA/blob/main/Mobile%20Reviews%20Sentiment.csv)
The dataset includes:

- `brand`  
- `rating`  
- `camera_rating`  
- `battery_rating`  
- `display_rating`  
- `performance_rating`  
- `price_usd` 
- `sentiment` (positive / neutral / negative)  
- `source` (review platform)  
- `country` (reviewer country)

---

## 🔧 Steps Performed

### **1. Initial Data Inspection**
- Viewed first rows, shape, column types  
- Counted missing values  
- Reviewed distributions and value counts  

### **2. Data Cleaning**
- Handled missing values  
- Converted numeric columns  
- Prepared cleaned dataset for analysis  

### **3. Exploratory Data Analysis (EDA)**

#### ✔ Ratings per Brand  
Analyzed average user rating for each brand.

#### ✔ Spec Ratings  
Compared average:  
- Camera  
- Battery  
- Display  
- Performance  

#### ✔ Price Analysis  
Compared brand price segments  
(Apple/Samsung premium → Realme/Xiaomi cheapest).

#### ✔ Sentiment Distribution  
Visualized positive/neutral/negative reviews for each brand.

#### ✔ Country vs. Mobile Origin  
Evaluated whether users prefer phones from certain countries.

---

## 📊 Key Insights

### **1. Brand Ratings & Satisfaction**  
- All brands have **similar overall ratings**.  
- Users across segments appear generally satisfied.  
- **Apple** leads in camera satisfaction.  
- **Realme** performs extremely well relative to price.

---

### **2. Spec-Based Insights**

#### **Camera Satisfaction**
Apple clearly tops the camera satisfaction list — consistent with its premium image.

#### **Display Satisfaction**
- **Realme** ranks **first** in display satisfaction.  
- **Samsung ranks last**, even though globally known for high-quality screens.  
  This suggests a gap between user expectations and experience.

#### **Performance Satisfaction**
Realme performs extremely well — often outperforming mid-range and premium phones.

#### **Realme: Top 3 Across All Specs**
Realme ranks in the **top 3 for:**
- Camera  
- Battery  
- Display  
- Performance  

➡️ Making it the most **well-rounded value brand** in the dataset.

---

## 💰 Price Insights
Actual prices show:

- **Apple & Samsung** → most expensive  
- **Google & OnePlus** → mid-premium  
- **Realme & Xiaomi** → cheapest  
- **Motorola** → budget / mid-range  

**Core Insight:**  
➡️ Higher price does **not** lead to higher satisfaction.  
Budget phones frequently receive ratings comparable to premium ones.

---

## 🌍 Country–of–Origin Findings  
Brand origins:

- USA → Apple, Google  
- China → Xiaomi, Realme, OnePlus, Motorola  
- South Korea → Samsung  

User ratings show:

- **No meaningful national bias**  
- Users rate based on experience, not brand origin  
- Indian, American, and European users all scored phones consistently  

---

## 🙂 Sentiment Distribution  
- Majority of reviews are **positive**  
- Premium users (Apple, Samsung) tend to be more critical  
- Budget users (Xiaomi, Realme) reward good value-for-money  

---

## 🧠 Final Conclusion

### ⭐ **User ratings are always relative to price.**

A €1,500 iPhone may objectively outperform a €200 Xiaomi —  
but reviewers judge their phone based on **value for the money**, not raw specs.

- Premium buyers expect perfection → small flaws lower ratings  
- Budget buyers expect value → good performance increases ratings  

➡️ This is why **Realme and Xiaomi score as high as Apple and Samsung**, despite costing much less.  
➡️ "Perceived value" is the strongest driver of satisfaction.

---

## 🛠️ Technologies Used
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Jupyter Notebook  

---
