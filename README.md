# Call-Canter-Dashbord-Power-Bi
Interactive Power BI dashboard for Call Center performance analysis. Tracks CSAT, call duration, response time, sentiment, and channel efficiency.


لوحة تحكم تفاعلية مبنية بـ *Power BI* لتحليل أداء مركز الاتصال (Call Center).

## المميزات الرئيسية
- متوسط رضا العملاء (CSAT Score)
- متوسط وإجمالي مدة المكالمات
- وقت الاستجابة (Response Time)
- تحليل المشاعر (Sentiment: Positive / Negative / Neutral ...)
- أكثر أسباب المكالمات شيوعًا
- مقارنة بين قنوات التواصل (Phone, Email, Chatbot, Web ...)

## لقطات من الـ Dashboard

### الصفحة الرئيسية (Home Page)
![Home Page - نظرة عامة على الـ Dashboard](screenshots/main-dashboard.png)

### متوسط درجة رضا العملاء (Avg CSAT Score - Year)
![KPI - متوسط CSAT Score على مستوى السنة](screenshots/KPI-Avg-CSAT-Score-Year.png)

### متوسط مدة المكالمة (Avg Call Duration)
![KPI - متوسط مدة المكالمة مقارنة بالهدف](screenshots/KPI-Avg-Call-Duration.png)

### رضا العملاء وعدم الرضا حسب قنوات التواصل
![تحليل الرضا وعدم الرضا حسب القنوات](screenshots/dissatisfaction-and-satisfaction.png)

### أقل قناة تستهلك وقت
![أقل قناة استهلاكًا للوقت](screenshots/Less-time-consumption.png)

### أفضل قناة من حيث وقت الاستجابة (Response Time)
![أفضل قناة في وقت الاستجابة](screenshots/response-time.png)

## كيفية استخدام المشروع
1. قم بتنزيل ملف الـ *.pbix* من الريبو
2. افتح الملف باستخدام *Power BI Desktop*
3. إذا لم تظهر البيانات → غيّر مسار مصدر البيانات من داخل Power BI (Get Data → Edit Queries)

## الملفات المهمة
- Call Center Dashboard.pbix ← الملف الرئيسي للتقرير
- مجلد screenshots/ ← لقطات شاشة للصفحات المختلفة

## ملاحظات
- البيانات المستخدمة وهمية / anonymized
- تم بناء الـ dashboard باستخدام DAX measures و visuals متنوعة (KPI, Cards, Bar charts, Treemap ...)

Made with ❤️ in Egypt
