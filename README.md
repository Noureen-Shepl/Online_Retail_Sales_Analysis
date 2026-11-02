# Online Retail — Business Questions and Sales Analysis

A complete **descriptive analytics** portfolio project using the UCI Online Retail transactions. It does **not** train a machine-learning model.

## Scope
- Quality audit and transparent cleaning rules
- Gross positive merchandise sales, customer RFM segmentation
- Product, time, country, customer correlation and co-purchase analysis
- IQR outlier review and evidence-based business findings
- Six-panel Matplotlib dashboard (`outputs/sales_dashboard.png`)

## Run
1. Install `pip install -r requirements.txt`.
2. Keep `online_retail.csv.gz` beside the notebook.
3. Open `Online_Retail_Sales_Analysis_Completed.ipynb` and **Run All**.
4. Review figures and CSV summaries under `outputs/`.

## Data notes
One row is one invoice line. Cancellations, non-merchandise charges, duplicates, invalid dates, and nonpositive quantity/price are excluded from positive merchandise sales. This is **not** net sales or profit. Unidentified customers remain in sales but are excluded from RFM. Large wholesale orders are not removed automatically.

## Portfolio description (Arabic)
مشروع تحليل بيانات مبيعات متجر إلكتروني باستخدام Python وPandas، يشمل فحص جودة البيانات وتنظيفها، وتحليل العملاء باستخدام RFM، ودراسة المنتجات والمبيعات حسب الوقت والدول، واكتشاف المنتجات التي تُشترى معًا، وإعداد لوحة مؤشرات ورسوم بيانية. المشروع تحليلي وصفي ولا يتضمن تدريب نموذج تعلم آلي.
