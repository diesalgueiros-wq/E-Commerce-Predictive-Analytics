E-Commerce Predictive Analytics: VIP Segmentation and Potential Spend
This project implements a complete Machine Learning and Artificial Intelligence pipeline focused on the Retail / E-Commerce sector, utilizing the real-world Online Retail dataset from the UCI Machine Learning Repository.
The system cleans historical transactional data, calculates legitimate business metrics (RFM: Recency, Frequency, Monetary Value), and trains advanced models to identify high-value (VIP) customers and predict their future spending volume.
Architecture and Models Used
* Feature Engineering: Extraction of true Recency, Frequency, Monetary Value, and Product Variety (using real data, no synthetic datasets). Outlier treatment is handled via the Interquartile Range (IQR) method.
* Classification (VIP Segmentation): A performance comparison between Random Forest and XGBoost Classifier.
* Regression (Spend Prediction): A performance comparison between Random Forest and XGBoost Regressor.
* User Interface: An interactive search engine built with ipywidgets for rapid, real-time commercial queries.
Model Results
The classification model demonstrated optimal precision in identifying complex patterns of VIP behavior, outperforming traditional, fixed marketing rules. In the spend prediction section, XGBoost delivered the lowest Mean Absolute Error (MAE).
How to Run the Project
1. Open the notebook directly in Google Colab by clicking the Open in Colab button at the top.
2. Connect your Google Drive to manage persistent storage for the processed dataset.
3. Run the cells sequentially to train the models and deploy the interactive customer search tool.
