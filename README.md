# Sentiment-Insights-on-Amazon-Product-Reviews
This project is to analyze customer sentiments from Amazon product reviews based on both conventional Machine Learning and Deep Learning methods. The task is to classify reviews as positive, negative, or neutral from the text content.

Primary tasks:
1.Data cleaning and preprocessing of Amazon review datasets.
2.Comparison between ML models (e.g., Logistic Regression, SVM) and DL models (e.g., LSTM, BERT).
3.Performance metric evaluation using accuracy, precision, recall, and F1-score.

Tech Stack:
Languages: Python
Libraries: scikit-learn, TensorFlow/Keras, NLTK, pandas, NumPy, Matplotlib, seaborn
Tools: Jupyter Notebook / Google Colab  
Dataset: Amazon_Product_Clothing_Shoes_and_Jewelry

Project Structure:
.
├── README.md
├── data/
│   └── Amazon_Product_Clothing_Shoes_and_Jewelry.csv
├── preprocessing/
│   └── clean_data.py
├── models/
│   ├── ml_models.py
│   └── dl_models.py
├── results/
│   └── evaluation_metrics

Implementation:
Run ML and DL scripts to train sentiment analysis models.
Input any product review from the dataset to get its predicted sentiment.
Classify the input review as Positive, Negative or Neutral.  
Compare the ML and DL algorithms.

Output:
Model	Accuracies 
> Convolutional Neural Network 	91.1%
> Support Vector Machine	89.2%
> Random Forest	87.5%
> Logistic Regression	85.3%
