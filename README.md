# 🧩 Python Customer Segmentation Project — RFM Analysis & Clustering

This project demonstrates a **Python-only approach to Customer Segmentation**, focusing on **RFM (Recency, Frequency, Monetary) Analysis** and **KMeans Clustering**, commonly used for customer retention strategies in businesses.

## 🚀 Project Objectives
- Perform **RFM Feature Engineering** from raw transaction data.
- Apply **KMeans Clustering** for customer segmentation.
- Visualize customer profiles using **Seaborn Heatmaps**.
- Output clean segmented data for business usage (marketing, loyalty programs, etc).

## 🛠️ Tools & Libraries
- Python (Pandas, Numpy)
- Scikit-learn (KMeans, Silhouette Score)
- Seaborn & Matplotlib (Visualization)
- Jupyter Notebook / Python Scripts

## 📊 Workflow
1. **Data Loading**: Load customer transaction data (CSV).
2. **RFM Calculation**:
   - Recency: Days since last purchase.
   - Frequency: Number of purchases.
   - Monetary: Total amount spent.
3. **RFM Normalization** for clustering.
4. **KMeans Clustering**:
   - Elbow Method for optimal K.
   - Silhouette Score for quality validation.
5. **Cluster Profiling & Visualization**:
   - Seaborn Heatmaps to understand customer segments.
6. **Export Segments** to CSV for business applications.

## 📁 File Structure
<pre>
├── rfm_segmentation.ipynb
├── data/
│ └── Customer_Transactions.csv
├── outputs/
│ └── Customer_Segments_Output.csv
└── README.md
</pre>

## 📈 Example Visuals
- Elbow Curve (Optimal K Selection)
- Cluster Heatmaps (RFM Profile)
- Segmented Data Export for Marketing

## 🔑 Skills Demonstrated
- Python Data Analysis (Pandas)
- RFM Feature Engineering
- Clustering Algorithms (KMeans)
- Data Cleaning & EDA
- Visual Storytelling with Seaborn
- Problem Solving (Debugging Errors in Iterations)

## 🔗 Connect with Me
[https://www.linkedin.com/in/alieffadzil/] | [aleafdanial@gmail.com]

---

## 📌 Future Enhancements
- Automate the pipeline for regular transaction data ingestion.
- Apply more advanced clustering (DBSCAN, Hierarchical).
- Integrate with SQL-based ETL pipelines for scalable deployment.
