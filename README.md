# 🏠 Boston Housing Price Prediction

## 📌 Project Overview

هذا المشروع يهدف إلى تحليل بيانات **Boston Housing Dataset** وبناء نموذج تعلم آلي للتنبؤ بأسعار المنازل باستخدام **Linear Regression**.

---

## 🧰 Tools & Libraries

* Python 🐍
* NumPy
* Pandas
* Matplotlib
* Seaborn
* Scikit-learn

---

## 📊 Data Description

البيانات تحتوي على 506 سجل و 14 متغير، مثل:

* CRIM: معدل الجريمة
* RM: عدد الغرف
* AGE: عمر المنازل
* DIS: المسافة من مراكز العمل
* LSTAT: نسبة السكان ذوي الدخل المنخفض
* Price: سعر المنزل (Target)

---

## 🔍 خطوات العمل

### 1. تحميل البيانات

تم تحميل البيانات من:

```
http://lib.stat.cmu.edu/datasets/boston
```

---

### 2. تنظيف ومعالجة البيانات

* قراءة البيانات باستخدام Pandas
* دمج الصفوف
* إنشاء DataFrame منظم

---

### 3. التحليل الاستكشافي (EDA)

* عرض الإحصائيات باستخدام `describe()`
* رسم Histogram لتوزيع الأسعار
* رسم Heatmap لمعرفة الارتباطات
* استخدام Pairplot لاستكشاف العلاقات
* Scatter plot بين السعر وعدد الغرف

---

## 🤖 بناء النموذج

* تقسيم البيانات:

  * 60% تدريب
  * 40% اختبار

* استخدام نموذج:

```
Linear Regression
```

---

## 📈 النتائج

تم تقييم النموذج باستخدام:

* MAE (Mean Absolute Error):
  `3.54`

* RMSE (Root Mean Squared Error):
  `4.72`

* R² Score:
  (اكتب الناتج هنا لما يظهر عندك)

---

## 📊 Visualization

* Distribution of prices
* Correlation heatmap
* Feature relationships

---

## 🚀 How to Run

1. افتح الملف في Google Colab أو Jupyter Notebook
2. شغل الخلايا بالترتيب
3. تأكد من تثبيت المكتبات:

```
pip install numpy pandas matplotlib seaborn scikit-learn
```

---

## 💡 Notes

* تم استخدام بيانات كلاسيكية للتعلم والتجربة
* يمكن تحسين النموذج باستخدام:

  * نماذج أكثر تقدمًا
  * Feature Engineering
  * Cross Validation

---

## 👨‍💻 Author

* abdullahf-77
