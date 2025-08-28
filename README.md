# Email-Risk-Detection-Model
This project applies natural language processing and machine learning models to classify privacy risk levels in text based on the presence and type of personally identifiable information (PII) using the PII Masking 300K dataset. Texts are labeled with BIO-format PII tags according to the number and sensitivity of PIIs, and then the risk of unlabeled emails is classified using four models: logistic regression, multinomial naive Bayes with TF-IDF, DistilBERT, and GPT-3.5 via API. DistilBERT achieved the best overall performance with 0.99 precision and 0.87 recall on high-risk emails, minimizing false negatives when risky emails are not classified as such.

📄 [Read the full paper (PDF)](./report.pdf)  
📘 [Open the Jupyter Notebook](./code.ipynb)
