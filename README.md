# Kaggle Netflix Project 

#### Participants: Chang Du, Yunhe Cui, Junjie Cai, Xurui Chen, Tiancheng Yin

### Stage I: ETL 
- Extract: Data download from kaggle.com 
- Transform: Necessary preprocessing steps from high level (might not be useful)
- Load: Upload on AWS/Azure/Google Cloud in a querable format

### Stage II: Methods
#### 0) Data Preprocessing 
- N/A values handling (LR fill, intropolate, median, mean, 0, etc)
- feature engineering/feature selection
- PCA if necessary 
- outlier removal (based on IQR or customerized based on ML models)
#### 1) Machine Learning Methods 
- K-means
- Lasso/Ridge Regression
- Decision Tree (etc...)
- Random Forest Regressor 
- XgBoost Regressor (idealy this should be the best performer)
#### 2) Collaborative Filtering 
- Recommendation system 
#### 3) Cosine Similarities Analysis 
- Rating prediction based on cosine similarities 
### Stage III: Deployment 
- Spark/MapReduce procedure 
### Stage IV: Optimization 
- Try different methods 
### Stage V: Project Website & Report 
- Full stack website with front-end and back-end database 
- Support real-time big data analysis 
