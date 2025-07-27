# 📊 Student Performance Analysis

## 🔍 نظرة عامة
هذا المشروع يهدف إلى تحليل أداء الطلاب في مادة الرياضيات باستخدام بيانات من Kaggle، ودراسة تأثير عوامل مثل:
- النوع (Gender)
- الدورة التحضيرية (Test Preparation Course)
- مستوى تعليم الأهل (Parental Education Level)

تم استخدام أدوات تحليل البيانات والتصور البياني لاستخراج الرؤى وتقديم استنتاجات مفيدة.

---

## 🛠️ الأدوات المستخدمة
- Python
- Pandas
- Matplotlib
- Seaborn

---

## 📂 هيكل المشروع


Student_Performance_Analysis/
│
├── README.md ← وصف المشروع
├── notebook.ipynb ← الكود والتحليل (Jupyter Notebook)
├── data/
│ └── StudentsPerformance.csv
├── images/ ← صور الجرافيكس
---

---

## 📈 أمثلة من التحليل
### توزيع درجات الرياضيات:
![Math Distribution](images/math_distribution.png)

### تأثير الدورة التحضيرية على الدرجات:
![Preparation Effect](images/preparation_boxplot.png)

---

## ✅ الاستنتاجات
- الطلاب الذين أكملوا الدورة التحضيرية حققوا درجات أعلى.
- هناك فرق بسيط لصالح الذكور في درجات الرياضيات.
- كلما ارتفع مستوى تعليم الأهل، ارتفعت درجات الطالب.

---

## 🚀 كيفية التشغيل
1. حمّل البيانات من Kaggle: [Students Performance Dataset](https://www.kaggle.com/datasets/spscientist/students-performance-in-exams)
2. افتح ملف `notebook.ipynb`.
3. شغّل جميع الخلايا بالترتيب.

---

## 📌 تطويرات مستقبلية
- إضافة نماذج تنبؤية (Predictive Models).
- تحليل باقي المواد (Reading, Writing).
- بناء لوحة تفاعلية (Dashboard) باستخدام Plotly أو Streamlit.

