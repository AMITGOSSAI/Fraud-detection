The increasing volume of online transactions raises the constant danger of fraud and dishonest business 
practices that compromise individual privacy. Many commercial banks and insurance companies have 
invested millions of rupees in developing transaction detection systems to stop high-risk transactions. This 
research study presents a feature-engineered, machine learning-based model for identifying transaction 
fraud. The algorithm can improve its performance, stability, and gain experience by processing large 
amounts of data. These algorithms are used to analyse datasets of online transactions, identifying 
anomalous or unique data patterns indicative of fraud.
To deploy a online payment system effectively, it is necessary to minimize fraud to increase customer trust 
and security, as highlighted in existing online payment acceptance models. The growing use of online 
payments has increased the risk of fraud, pressuring the need to investigate and prevent potential security 
threats. Early detection of fraudulent transactions is crucial. Therefore, recent advancements in mobile 
payment services have underscored the need for automated detection systems that provide immediate 
fraud detection and prevention.
Researchers face several challenges in detecting fraud in online payment transactions: 1.Extreme Class 
Imbalance: The significant imbalance between legitimate and fraudulent transactions can lead to poor user 
experiences for legitimate customers and decreased detection model performance. 2.Evolving Fraud 
Patterns: Fraudsters constantly adapt, necessitating continuous updates to detection models.
3.Performance Metrics Selection: Balancing false positives and false negatives is challenging, as providers 
must choose the right ratio between these errors for optimal fraud detection. Previous research has 
reported high detection accuracy using traditional supervised learning methods and deep learning-based 
methods. However, these methods struggle with class imbalance, leading to poor classification performance 
for the minority class of fraudulent transactions. Approaches that have been utilized to address this issue1. Under-sampling: Generates a balanced dataset but risks losing important information from legitimate 
transactions, reducing detection accuracy.
2. Over sampling: Oversampling involves increasing the number of instances of the minority class to 
balance the class distribution in the dataset.
• SMOTE (Synthetic Minority Over-sampling Technique): SMOTE generates synthetic samples by 
interpolating between existing minority class instances. It selects two or more similar instances and 
creates new, synthetic instances along the line segments joining them. This technique helps in 
reducing overfitting compared to random oversampling.
3. Fuzzy C-means clustering: A custom sampling technique to improve the representativeness of the 
sampled data.
The results, derived from the PaySim and credit card dataset, showcase the effectiveness of both XGBoost 
with an under-sampling and over sampling class-balancing technique and extreme gradient boosting outlier 
detection (XGBOD). These methods offer vital tools to enhance the operation and management of online
payment services.
