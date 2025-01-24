# Agricultural Data Engineering Pipeline 🌾

A modern data pipeline leveraging AWS S3, Databricks, and MongoDB Atlas to process, analyze, and store agricultural metrics across countries.

## Architecture Overview 📊
- Data Storage: AWS S3
- Processing Engine: Databricks (PySpark)
- Analytics Database: MongoDB Atlas
- Visualization: Matplotlib/Seaborn

## Infrastructure Setup ⚙️

### Cloud Components
- Databricks Runtime 15.4 LTS 🔧
- AWS S3 Bucket ☁️
- MongoDB Atlas Cluster 🗄️

### Dependencies 📚
```python
pyspark
pymongo
matplotlib 
seaborn
pandas
numpy
certifi
```

### Authentication Configuration 🔑
- IAM Role for S3 Access
- Reference: [Databricks S3 Access Guide](https://gist.github.com/ifyjakande/3db382f383078832abd81f5cf3449ad6)

## Data Pipeline 🔄
### Sources 
- `Cereal_Yield.xls`: Agricultural yield metrics 🌽
- `Land_Use.xls`: Geographical data 🗺️

### Processing Features
- ETL Workflow & Data Cleaning 🧹
- Statistical Analysis 📊
- Automated Insights Generation 🤖
- Time Series Visualization 📈
- MongoDB Integration for Results Storage 💾

## System Architecture 🏗️
![Pipeline Architecture](/reco-system/architecture.jpg)

## Sample Output 📊
![Pipeline Results](/reco-system/mongodb-data1.jpg)

## License 📄
MIT
