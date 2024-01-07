INSURANCE CLAIM ANALYSIS
------------------------


📥 Data Ingestion and Storage:

The pipeline begins by ingesting raw insurance data into a Raw Bucket within Google Cloud Storage—a temporary holding area for unprocessed data.



🗃 Data Lake Organization:

Meticulously organized into three buckets:

💠 Raw Bucket: Stores the raw, unaltered insurance data.

💠 Cleansed Bucket: Holds data after basic cleaning and preparation.

💠 Curated Bucket: Contains highly refined and structured data, ready for analysis.



🔄 Data Processing and Transformation:

🧹Data Cleaning: Google Cloud Functions diligently handle missing values, correct inconsistencies, and format data appropriately within the Cleansed Bucket.

🎭Data Transformation: Additional Cloud Functions transform data within the Curated Bucket, converting CSV files to JSON format, and adding aggregated columns.



📊 Data Analysis and Visualization:

🔍Data Source: The insurance data serves as the foundation, driving insights throughout the pipeline.

🏦Data Warehousing: Cleansed and curated insurance data is stored in Google BigQuery, a cloud-based data warehouse optimized for large-scale analytics.

🎨Visualization: Tableau connects seamlessly to BigQuery, creating interactive visualizations and dashboards for effective data exploration and analysis.



💻 Technology Used:

🔵  Google Cloud Platform (GCP): Leveraging cloud-based infrastructure for storage, processing, and analysis, offering unparalleled scalability and flexibility.

🔵 Google Cloud Functions: Utilizing serverless functions for efficient data cleaning and transformation without the need for dedicated servers.

🔵 Google BigQuery: The go-to cloud-based data warehouse for staged data processing and storage.

🔵 Tableau: The dynamic business intelligence tool that connects seamlessly to BigQuery for comprehensive data analysis and visualization.



🚀 Key Points:

🔷 Cloud-Based Infrastructure: Scalability and flexibility at the core, thanks to GCP.

🔷 Staged Data Processing: A multi-stage approach ensures gradual refinement from Raw to Cleansed and Curated buckets.

🔷 Serverless Functions: Efficient data cleaning and transformation with the agility of Google Cloud Functions.

🔷 Data Warehousing and Visualization: Integration with BigQuery and Tableau for comprehensive insurance data analysis and insightful visualization.
