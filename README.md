#**📦 FedEx Logistics — Exploratory Data Analysis (EDA)**

**🧭 Project Overview**
This project analyzes FedEx Logistics data (10,324 rows, 33 columns) to identify inefficiencies in shipment modes, delivery timelines, and vendor performance. The goal is to optimize shipment efficiency, reduce costs, and improve delivery performance, enabling FedEx to make data-driven decisions for smarter, faster, and more cost-effective logistics operations.

**💼 Business Objectives**

* Streamline supply chain operations: Identify bottlenecks to ensure timely deliveries.
* Minimize freight costs: Optimize routing, carrier selection, and vendor contracts.
* Improve customer satisfaction: Enhance service quality and proactively address delivery issues.

**📊 Dataset Overview**
* Rows & Columns: 10,324 rows, 33 columns

**Key Columns:**
1. Country
2. Shipment Mode
3. Delivery Timelines
4. Product Details
5. Vendor Information
6. Delivery Cost & INCO Terms

**🔧 Data Preprocessing & Feature Engineering**
* Converted date columns to datetime format for accurate analysis.
* Removed PO Sent to Vendor Date due to excessive missing data.
* Filled missing values in Dosage using mode.
* Detected outliers using IQR method.
* Created Delivery Time = Delivered to Client Date − Scheduled Delivery Date to analyze on-time vs delayed deliveries.

**📈 Key Analyses**
1. On-Time Delivery Rate: Patterns of late deliveries by country, vendor, and transport mode.
2. Transport Cost Analysis: Freight cost variations across vendors, shipment modes, and INCO terms.
3. Vendor & Product Performance: Evaluated vendor efficiency and product trends.
4. Freight Cost vs Shipment Mode: Compared air, sea, and road shipments for cost-speed balance.
5. Brand vs Price Trend: Identified high-demand, low-cost brands.

**💡 Insights & Recommendations**
1. Strengthen Vendor Relationships: Negotiate with high-cost vendors and reward reliable ones.
2. Leverage Mixed Shipment Modes: Use air for urgent deliveries, sea/road for bulk non-urgent shipments.
3. Optimize Transport Costs: Streamline shipping routes and renegotiate freight contracts.
4. Select Cost-Effective INCO Terms: Balance cost-efficiency and risk-sharing.
5. Enhance Logistics Efficiency: Expand warehouses and improve routing in low-performing regions.
6. Improve Customer Experience: Focus on on-time delivery and proactive delay management.

**🧠 Conclusion**
The EDA provided actionable insights to improve cost efficiency, vendor performance, and delivery accuracy. FedEx can leverage these findings to implement data-driven logistics strategies, optimize freight operations, and enhance customer satisfaction—ensuring sustainable growth and operational excellence in its global supply chain.
