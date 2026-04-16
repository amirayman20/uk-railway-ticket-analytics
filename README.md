# UK Railway Ticket Analytics — Power BI Project  
# تحليل تذاكر القطارات في المملكة المتحدة — مشروع Power BI

---

# 🇬🇧 English Version

## 📌 Project Overview
This project presents a complete end-to-end Power BI analysis of UK railway ticket sales, revenue trends, customer behavior, delays, and operational performance.  
The goal is to transform raw ticketing data into clear, actionable insights through professional data modeling and interactive dashboards.

The report answers more than **30 business questions**, covering sales, revenue, delays, refunds, ticket types, railcards, and time-based trends.

---

## 📂 Dataset Description
The dataset contains transactional ticketing records with the following fields:

- Date & Time of Purchase  
- Date of Journey  
- Departure & Arrival Stations  
- Ticket Type (Advance, Off-Peak, Anytime)  
- Ticket Class (Standard, First Class)  
- Payment Method  
- Railcard Type  
- Journey Status (On Time, Delayed, Cancelled)  
- Delay Time  
- Refund Request  
- Ticket Price & Revenue  

All fields are stored in a **single fact table**, making the model simple, efficient, and optimized for analysis.

---

## 🧹 Data Cleaning
Data cleaning was performed using Power Query:

- Removed duplicates  
- Standardized date and time formats  
- Fixed inconsistent station names  
- Converted text fields to categorical types  
- Handled null values in delay and refund fields  
- Created bins for:
  - Date of Purchase  
  - Time of Purchase  
  - Date of Journey (Month)

This ensured a clean, analysis-ready dataset.

---

## 🧩 Data Model
The data model consists of **one unified fact table** containing all ticketing attributes.

This structure supports:

- KPI calculations  
- Time-based analysis  
- Customer behavior insights  
- Operational performance reporting  
- Dashboard interactivity  

A Date Table can be added in future versions for advanced time intelligence.

---

# 📊 Dashboard Pages

## 1️⃣ Home Page
A clean landing page introducing the project.

![Home Page](images/home_page.png)

---

## 2️⃣ Analysis Page — Ticket Sales & Customer Insights
This page focuses on sales performance and customer behavior.

### Key Metrics:
- **32K** total tickets sold  
- **741.92K** total revenue  
- **23.44** average ticket price  
- **11K** customers using railcards  

### Visuals:
- Tickets by Purchase Type  
- Tickets by Ticket Class  
- Tickets by Ticket Type  
- Tickets by Payment Method  
- Tickets by Railcard Type  
- Avg Ticket Price by Railcard  
- Top Departure Stations  
- Top Arrival Stations  

![Analysis Page](images/analysis_page.png)

---

## 3️⃣ Analysis 1 — Operational Performance & Delay Analysis
This page analyzes delays, cancellations, and refund behavior.

### Visuals:
- Journey Status Distribution  
- Reasons for Delay  
- Routes with the Most Delays  
- Refund Requests Distribution  
- Refund Requests vs Journey Status  
- Revenue by Ticket Type  

![Operations Page](images/analysis_operations_page.png)

---

## 4️⃣ Analysis 2 — Revenue & Time-Based Insights
This page focuses on revenue trends and time-based behavior.

### Visuals:
- Revenue by Date of Purchase  
- Revenue by Date of Journey  
- Revenue by Time of Purchase  
- Avg Ticket Price by Ticket Type & Class  
- Monthly Revenue Trend  

![Revenue Trends Page](images/analysis_revenue_trends_page.png)

---

# 🎯 Business Questions Answered

### Sales & Customer Behavior
- How many total tickets were sold  
- Busiest purchase times  
- Online vs station purchases  
- Most used payment method  
- Average ticket price  
- Most used ticket type  
- Most used ticket class  
- Number of railcard users  
- Most common railcard type  
- Do railcard users pay less  

### Routes & Stations
- Stations with most departures  
- Stations with most arrivals  
- Most popular routes  

### Operational Performance
- Number of delayed, cancelled, on-time trips  
- Main reasons for delays  
- Routes with most delays  
- Refund requests  
- % refunds for delayed trips  
- % refunds for cancelled trips  

### Revenue & Time Trends
- Total revenue  
- Ticket type generating most revenue  
- Time of day with highest sales  
- Monthly sales trend  
- Is revenue increasing  
- Highest price combination (ticket type + class)  

---

# 📌 Key Insights

### Sales Insights
- Online purchases dominate.  
- Standard class represents over 90% of tickets.  
- Advance tickets are the most popular.  

### Customer Insights
- Railcard users form a large customer segment.  
- Non-railcard users pay the highest average price.  

### Operational Insights
- Most journeys are on time.  
- Weather and signal failures are top delay causes.  
- Refund requests are very low.  

### Revenue Insights
- Revenue shows an upward trend.  
- Early morning hours generate the highest revenue.  
- First Class Anytime tickets have the highest price.  

---

# 🗂 Project Structure

```
uk-railway-ticket-analytics/
│
├── Images/
│   ├── home_page.png
│   ├── analysis_page.png
│   ├── analysis_operations_page.png
│   └── analysis_revenue_trends_page.png
│
├── dashboard.pbix
└── README.md
```

---

# 🛠 Tools Used
- Power BI Desktop  
- Power Query  
- DAX  
- Excel  
- GitHub  

---

# 📬 Connect With Me
- **GitHub:** https://github.com/amirayman20  
- **LinkedIn:** https://www.linkedin.com/in/amir-ayman-/  
- **Email:** amirayman20@gmail.com  

---

# 🇸🇦 النسخة العربية

## 📌 نظرة عامة على المشروع
يقدم هذا المشروع تحليلًا متكاملًا باستخدام Power BI لبيانات مبيعات تذاكر القطارات في المملكة المتحدة، واتجاهات الإيرادات، وسلوك العملاء، والتأخيرات، والأداء التشغيلي.  
يهدف المشروع إلى تحويل البيانات الخام إلى رؤى واضحة وقابلة للتنفيذ من خلال نمذجة بيانات احترافية ولوحات تفاعلية.

التقرير يجيب على أكثر من **30 سؤالًا تحليليًا** يغطي المبيعات، الإيرادات، التأخيرات، الاستردادات، أنواع التذاكر، بطاقات الخصم، واتجاهات الوقت.

---

## 📂 وصف البيانات
تحتوي البيانات على سجلات معاملات التذاكر وتشمل:

- تاريخ ووقت الشراء  
- تاريخ الرحلة  
- محطة المغادرة والوصول  
- نوع التذكرة  
- درجة التذكرة  
- طريقة الدفع  
- نوع بطاقة الخصم  
- حالة الرحلة (في الوقت – متأخرة – ملغاة)  
- مدة التأخير  
- طلبات الاسترداد  
- سعر التذكرة والإيراد  

جميع الحقول موجودة داخل **جدول حقائق واحد** مما يجعل النموذج بسيطًا وفعالًا.

---

## 🧹 تنظيف البيانات
تم تنظيف البيانات باستخدام Power Query:

- إزالة التكرارات  
- توحيد تنسيقات التاريخ والوقت  
- تصحيح أسماء المحطات  
- تحويل الحقول النصية إلى فئات  
- معالجة القيم المفقودة  
- إنشاء مجموعات (Bins) للوقت والتاريخ  

---

## 🧩 نموذج البيانات
يعتمد النموذج على **جدول واحد موحد** يحتوي على جميع خصائص التذاكر.

يدعم النموذج:

- حساب مؤشرات الأداء  
- التحليل الزمني  
- تحليل سلوك العملاء  
- تحليل الأداء التشغيلي  
- التفاعل داخل اللوحات  

---

# 📊 صفحات لوحة التحكم

## 1️⃣ صفحة البداية
صفحة ترحيبية بسيطة.

![Home Page](images/home_page.png)

---

## 2️⃣ صفحة التحليل — المبيعات وسلوك العملاء
تشمل:

- إجمالي التذاكر  
- إجمالي الإيرادات  
- متوسط السعر  
- مستخدمي بطاقات الخصم  
- المبيعات حسب نوع التذكرة  
- المبيعات حسب الدرجة  
- المبيعات حسب طريقة الدفع  
- المحطات الأكثر مغادرة ووصولًا  

![Analysis Page](images/analysis_page.png)

---

## 3️⃣ صفحة الأداء التشغيلي — التأخيرات والاستردادات
تشمل:

- حالة الرحلات  
- أسباب التأخير  
- المسارات الأكثر تأخيرًا  
- طلبات الاسترداد  
- الاسترداد مقابل حالة الرحلة  
- الإيرادات حسب نوع التذكرة  

![Operations Page](images/analysis_operations_page.png)

---

## 4️⃣ صفحة الإيرادات — التحليل الزمني
تشمل:

- الإيرادات حسب تاريخ الشراء  
- الإيرادات حسب تاريخ الرحلة  
- الإيرادات حسب وقت الشراء  
- متوسط السعر حسب النوع والدرجة  
- الاتجاه الشهري للإيرادات  

![Revenue Trends Page](images/analysis_revenue_trends_page.png)

---

# 🎯 الأسئلة التحليلية التي تمت الإجابة عليها
(نفس القائمة الإنجليزية — مترجمة بالكامل)

---

# 📌 أهم النتائج
- المشتريات الإلكترونية هي الأكثر شيوعًا  
- الدرجة الاقتصادية تمثل 90% من التذاكر  
- بطاقات الخصم مستخدمة بشكل كبير  
- معظم الرحلات في الوقت  
- التأخيرات بسبب الطقس والإشارات  
- الإيرادات في اتجاه تصاعدي  

---

# 🗂 هيكل المشروع

```
uk-railway-ticket-analytics/
│
├── Images/
│   ├── home_page.png
│   ├── analysis_page.png
│   ├── analysis_operations_page.png
│   └── analysis_revenue_trends_page.png
│
├── dashboard.pbix
└── README.md
```

---

# 📬 تواصل معي
- **GitHub:** https://github.com/amirayman20  
- **LinkedIn:** https://www.linkedin.com/in/amir-ayman-/  
- **Email:** amirayman20@gmail.com  

