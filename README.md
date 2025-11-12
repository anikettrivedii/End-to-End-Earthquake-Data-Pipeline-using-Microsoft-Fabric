# 🌍 End-to-End Earthquake Data Pipeline — Microsoft Fabric | PySpark | Power BI

### **Project Overview**
This project demonstrates an end-to-end **data engineering workflow** for analyzing global earthquake events using **Microsoft Fabric**, **PySpark**, and **Power BI**.  
It automates the process of **fetching**, **cleaning**, **transforming**, and **visualizing** real-world earthquake data from the **USGS Earthquake Catalog**, following a **Medallion (Bronze → Silver → Gold)** architecture for structured, scalable analytics.

---

### **🧰 Tools & Technologies Used**
- **Microsoft Fabric**
  - Notebook for data ingestion, preprocessing, and transformation  
  - Data Pipeline for workflow automation and orchestration  
- **PySpark** — for distributed data processing and transformation  
- **Power BI** — for interactive dashboards and reporting  
- **USGS Earthquake API** — live source for real-time global earthquake data  
- **Delta Lake / Lakehouse Architecture** — for efficient storage and versioned datasets  

---

### **⚙️ Project Workflow**

**1. Data Ingestion**  
Automated ingestion from the [USGS Earthquake API](https://earthquake.usgs.gov) using Microsoft Fabric pipelines.  
Raw JSON data is stored in the **Bronze layer** for traceability and reproducibility.

**2. Data Cleaning & Transformation**  
Data is flattened, cleaned, and enriched in **Fabric Notebooks** using **PySpark** — producing standardized schema outputs in the **Silver layer**.

**3. Data Aggregation & Modeling**  
Aggregated metrics like daily counts, max magnitude, and regional summaries are computed in the **Gold layer** for analytics.

**4. Visualization & Reporting**  
Cleaned datasets are connected to **Power BI**, showcasing:
- Global earthquake activity trends  
- Magnitude frequency analysis  
- Regional and temporal heatmaps  

---

### **📊 Key Insights**
- Interactive visualizations of earthquake magnitudes and frequencies across regions  
- Time-based trend analysis showing active earthquake zones  
- Automated, scalable data pipeline showcasing modern **data engineering principles**  

---

### **🌐 Explore**
🔗 **Data Source:** [USGS Earthquake Catalog](https://earthquake.usgs.gov)  
📈 **Power BI Dashboard:** *(https://app.powerbi.com/view?r=eyJrIjoiMGI4NjQ1ZWEtNmZkNS00ZGUyLTk1OWItOTk3ZmM3YTEyZmE2IiwidCI6Ijc1NjMwNDliLTJmMWQtNDJlNC04MTY5LTA5NWFiNzM0Y2YwYyJ9)*  

---

### **💻 How to Run the Project**
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/earthquake-data-pipeline.git

