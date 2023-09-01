# Youtube-Data-Analysis
The primary objective of this project is to establish a secure and efficient system for managing, organizing, and deeply analyzing structured and semi-structured data derived from YouTube videos. The primary focus will be on extracting insights and making informed decisions based on video categories and trending metrics.

# Goals of the Project

- Data Ingestion: Develop a robust mechanism to collect data from diverse sources.
- ETL System: Transform raw data into the required format, ensuring its consistency and usefulness.
- Data Lake: Establish a centralized repository, a data lake, to accommodate data from multiple sources.
- Scalability: Design the system to seamlessly handle the growing volume of data.
- Cloud Integration: Leverage AWS cloud services due to the vast data scale, utilizing Amazon S3 as the storage backbone.
- Access Management: Employ AWS IAM for secure identity and access management.
- Reporting: Construct an interactive dashboard using Amazon QuickSight to obtain insights from the collected data.
- Data Integration: Utilize AWS Glue for effortless discovery, preparation, and fusion of data for analysis.
- Serverless Processing: Implement AWS Lambda for running code without the need to manage servers.
- Querying Simplification: Employ AWS Athena for on-demand querying of data stored in Amazon S3.

# Dataset Used:
The project will leverage a Kaggle dataset that encompasses statistical information (in CSV files) about daily popular YouTube videos across numerous months. The dataset covers up to 200 trending videos per day across various geographical locations. Each regional dataset contains data on video titles, channel titles, publication timestamps, tags, views, likes, dislikes, descriptions, and comment counts. Furthermore, a category_id field, distinct for each region, is integrated into the JSON file linked to that specific area. https://www.kaggle.com/datasets/datasnaek/youtube-new

# Architecture Overview


![Data Flow Architecture](https://github.com/amisha-21/Youtube-Data-Analysis/assets/77116519/3b52758e-6565-4393-b1a0-151085aaac47)





