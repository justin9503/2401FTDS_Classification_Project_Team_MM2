# Maji_Ndongo's News_24

<img src="https://png.pngtree.com/thumb_back/fh260/background/20230910/pngtree-newspaper-image_13202670.png">

## Table of Content:
* **1.** Project Overview
* **2.** Importing Packages
* **3.** Loading Data
* **4.** Data Cleaning
* **5.** Data Prepocessing
* **6.** Exploratory Data Analysis (EDA)
* **7.** Modelling
* **8.** Model Evaluations Metrics
* **9.**. Model Performance analysis
* **10.** Recommendations
* **11.** Reference
* **12.** Link to Our streamlit Application
* **13.** Team Mmembers
* **14.** Conclusion 

## 1.  Project Overview
## Project Overview: Maji_ndongo's News_24

In the digital age, the volume of news articles published online has increased exponentially, covering a wide range of topics and domains such as Business, Technology, Sports, Education, and Entertainment. This project aims to address the challenge of categorizing news articles into their respective domains using advanced machine learning techniques. By developing a robust classification model, we can enhance content management systems, improve user experience on news platforms, and enable more effective targeting for advertisers.

## 2. Importing Packages
* **Data Loading, Manipulation, and Analysis:** Pandas, CSV, String, re, NLTK, WordCloud, NumPy
* **Data Visualization:** Matplotlib, Seaborn

## 3. Loading Data

The data used for this project is located in the Data folder, which contains two files: test.csv and train.csv. The data was loaded into Pandas DataFrames using the pd.read_csv() function and referred to as train_data and test_data. The index_col=False parameter was implemented to demonstrate the column index in the DataFrame.

## 4.  Data Cleaning

Data cleaning involves correcting or removing incorrect, corrupted, duplicate, or incomplete data within a dataset. Techniques used include filling missing values, removing outliers, and standardizing data formats to ensure accuracy and reliability.

## 5.  Data Preprocessing
Data preprocessing involves preparing text data for analysis by:

* Downloading NLTK packages
* Loading datasets
* Cleaning text by removing noise, punctuation, converting to lowercase, and removing contractions
* Tokenizing text, removing stop words, and performing stemming and lemmatization
* Reassembling processed text into strings, with an option to save the cleaned datasets to CSV files

## 6. Exploratory Data Analysis (EDA)
EDA helps in understanding the variables and relationships within the dataset through:

* Investigating and summarizing the DataFrame's main characteristics using data visualization methods and statistical analyses
* Drawing meaningful insights to guide further research and data-driven decision making

## 7. Modelling
The following machine learning models were used:

* Logistic Regression
* Naive Bayes
* Support Vector Machine (SVM)
* Random Forest
* Adaboost
* Bagging

## 8. Model Evaluation Metrics

* Accuracy: The ratio of correctly predicted instances to the total instances.
* Precision: The ratio of correctly predicted positive observations to the total predicted positives.
* Recall: The ratio of correctly predicted positive observations to the all observations in actual class.
* F1 Score: The weighted average of Precision and Recall.

## 9. Model Performance Analysis

* Logistic Regression: High accuracy and F1 score, balanced precision, and recall across all classes.
* Naive Bayes: Highest accuracy and F1 score, excellent precision and recall across all classes.
* SVM: Strong performance with high accuracy and F1 score, consistent across most classes.
* Random Forest: Decent accuracy and F1 score, good performance in some classes but slightly lower metrics compared to Naive Bayes and Logistic Regression.
* Recommendation: Naive Bayes stands out as the top-performing model, achieving the highest accuracy and F1 score, making it the recommended choice for this classification task based on the provided data and evaluation results.

## 10. Recommendations

**1.** Expand Dataset: Collect more data from other sources so as to enhance the model’s cross validation.
**2.** Integrate Metadata: I would use other metadata to augment the feature set (for instance, date of publication, the author and so on).
**3.** Ensemble Methods: Use concept weighting by combining many models into one, approaching the matter of combining from different angles and testing combinations of various methods.

## 11. References

**1.** Logistic Regression
**2.** Random Forest
**3.** EDA Techniques
**4.** Data Cleaning Techniques

## 12 The App was delivered to the  maji Ngondo Stakeholders, for testing of the models and Classifications, link below.
https://justin9503-news-classifier-base-app-h5anzs.streamlit.app/ 


## 13. Team Members<a class="anchor" id="team-members"></a>

| Name                                                                                        |  Email              
|---------------------------------------------------------------------------------------------|--------------------             
| Justin Ndivhuwo Tshifaro                                                | njtshifaro@gmail.com
| Sinenkosi Sikhakhane                                                                                  | sikhakhanesnenkosi@gmail.com
| Obed Segwate Mabowa                                                                            | mabowaobed98@gmail.com
| Ntokozo Sbusiso Hadebe                                                | bighope95@gmail.com
| Kentse Mphahlele                                      | kentsemphahlele@gmail.com
| Aiden Geluk                                                   | aidengeluk8@gmail.com

##  Conclusion
In conclusion this project underscores the critical role that machine learning can play in the automated classification of news articles. By leveraging a variety of models, we have demonstrated the potential to accurately categorize articles into domains such as Business, Technology, Sports, Education, and Entertainment. The Naive Bayes model, in particular, showed exceptional performance, suggesting its suitability for similar classification tasks. Moving forward, there is potential to enhance the model's accuracy and efficiency by incorporating more sophisticated techniques, such as ensemble methods or transformer-based models like BERT. Additionally, continuous updates to the dataset and model retraining will be essential to maintain high performance in the ever-evolving landscape of news media. This project provides a strong foundation for future work in content classification and recommendation systems.
