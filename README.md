# 📊 Sales Prediction using Python

## 🔹 Project Overview
This project focuses on predicting product sales based on advertising investments across different channels (TV, Radio, and Newspaper).
By leveraging Python for data analysis, visualization, and machine learning modeling, the goal is to understand how advertising spend influences sales and to build accurate predictive models.

## 🔹 Objectives
- Clean, explore, and visualize sales & advertising data.
- Identify correlations between ad spending and sales.
- Build regression models (Linear Regression, Random Forest) to predict sales.
- Evaluate model performance using metrics (MAE, RMSE, R²).
- Simulate scenarios (e.g., +10% ad spend) to measure impact on sales.
- Provide insights for data-driven marketing strategies.

## 🔹 Tools & Libraries
- Pandas → Data handling & preprocessing  
- NumPy → Numerical operations  
- Matplotlib & Seaborn → Data visualization  
- Scikit-learn → Machine learning models & evaluation  

## 🔹 Workflow
### Data Exploration & Cleaning
- Loaded dataset (Advertising.csv).
- Checked missing values, data types, and statistical summary.
- Explored correlations between features and sales.

### Exploratory Data Analysis (EDA)
- Scatter plots: Sales vs TV, Radio, Newspaper.
- Heatmap: Correlation matrix (TV had the strongest impact).
- Pairplot: Relationships between variables.

### Model Training
- Linear Regression: Built a baseline regression model.
- Random Forest Regressor: Applied an ensemble method for better accuracy.

### Model Evaluation
- Metrics: MAE, RMSE, R².
- Random Forest outperformed Linear Regression with higher accuracy.

### Scenario Analysis
- Simulated a 10% increase in ad spending.
- Observed noticeable improvement in average predicted sales.

### Visualization
- Regression lines for individual features (TV, Radio, Newspaper).
- 3D plot showing TV & Radio impact on sales.
- Bar chart comparing model performance metrics.

## 🔹 Key Findings
- TV advertising has the highest impact on sales.
- Radio contributes moderately, while Newspaper has minimal effect.
- Random Forest provided the most reliable predictions.
- A small increase in advertising budget can lead to measurable sales growth.

## 🔹 Business Impact
This analysis provides actionable insights for marketing teams:
- Focus more on TV & Radio campaigns for higher ROI.
- Reduce unnecessary spending on Newspaper ads.
- Use predictive modeling to forecast sales outcomes before running campaigns.

## 🔹 What I Learned
- Learned how to handle data from cleaning to building a prediction model.
- Understood the importance of Exploratory Data Analysis (EDA) before modeling.
- Practiced using different algorithms such as Linear Regression and Random Forest, and understood the differences between them.
- Gained experience in evaluating models using metrics like MAE, RMSE, and R².
- Trained on data visualization with Python libraries to present results more clearly.
- Understood how predictions can be used to support practical business and marketing decisions.

✅ Project Completed – A practical demonstration of how machine learning can support business decisions through data-driven sales predictions.

---

# 📊 التنبؤ بالمبيعات باستخدام Python

## 🔹 نظرة عامة على المشروع
يركز هذا المشروع على التنبؤ بالمبيعات بناءً على الاستثمارات الإعلانية عبر قنوات مختلفة (التلفاز، الراديو، والصحف).  
باستخدام Python في تحليل البيانات، التصور البياني، ونماذج التعلم الآلي، يهدف المشروع إلى فهم كيف يؤثر الإنفاق الإعلاني على المبيعات وبناء نماذج تنبؤية دقيقة.

## 🔹 الأهداف
- تنظيف البيانات واستكشافها وتصورها.  
- تحديد العلاقات بين الإنفاق الإعلاني والمبيعات.  
- بناء نماذج انحدار (Linear Regression, Random Forest) للتنبؤ بالمبيعات.  
- تقييم أداء النماذج باستخدام مقاييس (MAE, RMSE, R²).  
- محاكاة سيناريوهات (مثل: زيادة 10% في الإنفاق الإعلاني) لقياس الأثر.  
- تقديم رؤى عملية تدعم استراتيجيات التسويق.  

## 🔹 الأدوات والمكتبات
- Pandas → لمعالجة البيانات وتنظيفها.  
- NumPy → للعمليات العددية.  
- Matplotlib & Seaborn → للتصور البياني.  
- Scikit-learn → لبناء نماذج التعلم الآلي وتقييمها.

## 🔹 مراحل العمل
### استكشاف وتنظيف البيانات
- تحميل البيانات (Advertising.csv).
- التحقق من القيم المفقودة، أنواع البيانات، والإحصاءات الوصفية.
- دراسة العلاقات بين الخصائص والمبيعات.

### تحليل البيانات (EDA)
- رسوم Scatter: المبيعات مقابل (TV, Radio, Newspaper).
- خريطة حرارية: مصفوفة الارتباط (TV كان الأكثر تأثيرًا).
- Pairplot: العلاقات بين المتغيرات.

### تدريب النماذج
- الانحدار الخطي (Linear Regression): كنموذج أساسي.
- غابة عشوائية (Random Forest Regressor): لزيادة الدقة.

### تقييم النماذج
- المقاييس: MAE, RMSE, R².
- Random Forest أعطى دقة أعلى من Linear Regression.

### تحليل السيناريوهات
- محاكاة زيادة 10% في الإنفاق الإعلاني.
- ملاحظة تحسن متوسط في المبيعات المتوقعة.

### التصور البياني
- خطوط الانحدار لكل متغير (TV, Radio, Newspaper).
- رسم ثلاثي الأبعاد يوضح أثر TV و Radio على المبيعات.
- رسم أعمدة للمقارنة بين أداء النماذج.

## 🔹 أهم النتائج
- الإعلانات التلفزيونية لها التأثير الأكبر على المبيعات.
- الراديو له تأثير متوسط، بينما الصحف تأثيرها ضعيف جدًا.
- نموذج Random Forest كان الأكثر دقة وموثوقية.
- زيادة طفيفة في ميزانية الإعلان تؤدي إلى نمو ملحوظ في المبيعات.

## 🔹 الأثر العملي على الأعمال
هذا التحليل يقدم رؤى مفيدة لفرق التسويق:
- التركيز أكثر على حملات التلفاز والراديو لتحقيق عائد أعلى.
- تقليل الإنفاق غير الضروري على إعلانات الصحف.
- استخدام النماذج التنبؤية لتقدير نتائج المبيعات قبل تنفيذ الحملات.

## 🔹 ماذا تعلمت ؟
- اتعلمت إزاي أتعامل مع البيانات من أول تنظيفها لحد بناء نموذج تنبؤ.  
- عرفت أهمية تحليل البيانات الاستكشافي (EDA) قبل أي خطوة في النمذجة.  
- مارست استخدام خوارزميات مختلفة زي Linear Regression و Random Forest وفهمت الفرق بينهم.  
- اكتسبت خبرة في تقييم النماذج باستخدام مقاييس زي MAE, RMSE, R².  
- اتدربت على التصور البياني باستخدام مكتبات Python لعرض النتائج بشكل أوضح.  
- فهمت إزاي ممكن نستخدم التنبؤات لدعم قرارات عملية في مجال الأعمال والتسويق.  

✅ المشروع مكتمل – عرض عملي يوضح كيف يمكن لتقنيات تعلم الآلة أن تدعم القرارات التجارية من خلال تنبؤات المبيعات المبنية على البيانات.
