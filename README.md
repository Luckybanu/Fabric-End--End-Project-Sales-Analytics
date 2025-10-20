## Sales Analytics Modernization at GlobeSmart Electronics


Ingested staging sales data from **Azure Data Lake Storage Gen2 (ADLS Gen2)** into the **Bronze layer** using a **Fabric pipeline**

Transformed data through **Bronze → Silver → Gold** layers within a **Fabric Lakehouse**, using **PySpark notebooks** for cleaning, **SCD2 logic**, and **FX handling**, and SQL views for **star schema modeling**

Implemented **SCD Type 2** inside **Fabric Lakehouse** on customer and **event dimensions** to preserve historical tracking (e.g., customer tier changes, region reassignments)

Applied **currency normalization** & **USD conversion** to enable global sales reporting

Modeled a **business-ready star schema**(fact sales + multiple dimensions) in the **Gold layer**

Delivered **curated datasets** in Gold that can be connected to **Power BI** for insights
