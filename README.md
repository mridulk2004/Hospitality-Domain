
## Hotel Sales Performance Dashboard

*Purpose*  
This dashboard provides a comprehensive overview of hotel sales and operational performance across multiple cities and room types. It helps stakeholders quickly assess key business metrics, property performance, and revenue trends to support data-driven decision-making.

---

### Tech Stack

The dashboard was built using the following tools and technologies:

- 📊 *Power BI Desktop* – Main data visualization platform used for report creation.
- 📂 *Power Query* – Data transformation and cleaning layer for reshaping and preparing the data.
- 🧠 *DAX (Data Analysis Expressions)* – Used for calculated measures, dynamic visuals, and conditional logic.
- 📝 *Data Modeling* – Relationships established among tables to enable cross-filtering and aggregation.
- 📁 *File Format* – .pbix for development and .png for dashboard previews.

---

### Goal of the Dashboard

- Monitor and compare sales performance across cities, properties, and room types.
- Analyze occupancy, revenue, and key hotel metrics to inform operational and strategic decisions.
- Track trends in RevPAR, ADR, and occupancy over time.
- Identify top-performing properties and categories for targeted business strategies.
- Enable data-driven decisions for pricing, marketing, and inventory management.

---

### Walkthrough of Key Visuals

*Top Metrics Overview:*  
The dashboard highlights essential KPIs at the top, including:

| Metric        | Value    |
| ------------- | -------: |
| *Revenue*        | *1.69bn*   |
| *RevPAR*         | *7.34K*    |
| *DSRN*           | *2.53K*    |
| *Occupancy%*     | *57.79%*   |
| *ADR*            | *12.70K*   |
| *Realisation %*  | *70.14%*   |

---

*Day Type Comparison:*  

| Day Type | RevPAR   | Occupancy % | ADR      | Realisation % |
|----------|---------:|------------:|---------:|--------------:|
| Weekday  | 7,082.53 | 55.85%      | 12,682.41| 69.11%        |
| Weekend  | 7,971.63 | 62.64%      | 12,742.51| 71.16%        |
| *Total*| 7,336.56 | 57.79%      | 12,695.75| 70.14%        |

---

*Revenue by Category:*  
- *Luxury:* 61.62%
- *Business:* 36.38%

---

*Trend by Key Metrics:*  
A line chart tracks RevPAR, ADR, and Occupancy % over time, highlighting performance trends across weeks and months.

---

*Realisation % and ADR by Platform:*  
A combined bar and line chart displays Realisation % and ADR across different booking platforms.

---

*Property by Key Metrics:*  

| property_id | property_name   | city    | Revenue | RevPAR | Occupancy % | ADR    | DSRN | DBRN | DURN | Realisation % | Cancellation % |
|-------------|-----------------|---------|---------|--------|-------------|--------|------|------|------|---------------|----------------|
| 15658       | Atliq Grands    | Delhi   | 36M     | 7,525  | 61%         | 11,146 | 36   | 24   | 24   | 70.01%        | 6.5%           |
| 15659       | Atliq Exotica   | Delhi   | 36M     | 7,525  | 61%         | 11,146 | 36   | 24   | 24   | 70.01%        | 6.5%           |
| 17561       | Atliq Palace    | Mumbai  | 5M      | 7,097  | 56%         | 12,625 | 12   | 8    | 8    | 70.14%        | 7.0%           |
| ...         | ...             | ...     | ...     | ...    | ...         | ...    | ...  | ...  | ...  | ...           | ...            |
| *Total*   |                 |         | 168M    |        |             |        |      |      |      |               |                |

---

*Interactive Filters:*  
Users can filter data by city and room type for customized analysis.

---

### Business Impact & Insights

- Track revenue, occupancy, and ADR trends across cities, room types, and platforms.
- Identify high-performing properties and categories for targeted action.
- Support revenue management, pricing, and operational decisions with real-time insights.

---

![Dashboard Preview].(https://github.com/mridulk2004/Hospitality-Domain/blob/main/Hospitatlity%20Domain%20Dashboard.png)
