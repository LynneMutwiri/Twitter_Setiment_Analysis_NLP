# Sentimental Analysis
![moringa_phase4_project](https://github.com/Daniel1999Akama/moringa_phase4_project/assets/127243987/44675d35-58cc-411a-baa7-c3422ebfcd75)

## Table of Contents

- Sentimental Analysis
- Project Overview 
- Problem Statement 
- Data Understanding
- Methodology
- Evaluation
- Conclusion
- Recommendation
- Next Steps
- Installation
- Collaborators
- Repository Structure 

# Business understanding
In today’s digital age, social media platforms such as Twitter have become powerful sources of real-time customer feedback and opinions. Understanding the sentiment expressed by customers toward specific brands and products is essential for businesses to make informed decisions, enhance customer satisfaction, and maintain a positive brand reputation. 

The goal of this project aims to develop a sentimental analysis model specifically tailored to analyze Twitter data related to Google, Apple, and other products. 

# Business Problem Statement

As a consulting firm, Twitter has assigned us the task of building a model that can rate the sentiment of a Tweet based on its content  that can correctly categorize Twitter sentiment about Apple and Google products into positive, negative, or neutral categories and  gain valuable insights into public perception, that will be used for informed decision-making in business strategies and customer satisfaction enterprise.


# Data understanding
In this project, we analyze sentiment using a dataset of customer reviews collected from Twitter. The dataset contains a collection of text reviews and corresponding sentiment labels indicating whether the sentiment expressed in the review is positive, negative, or neutral. The dataset consists of 9093 rows and 3 columns.

To gain a better understanding of the data, we performed the following steps:

Data Collection: We collected the customer data world where there is a data set from from twitter platforms and review aggregators. The reviews were selected based on relevance to our analysis.

Data Preprocessing: We cleaned the raw text data by removing any irrelevant information, such as HTML tags, URLs, and special characters. We also performed tokenization, stop word removal, and stemming/lemmatization to normalize the text.

Exploratory Data Analysis (EDA): We conducted an in-depth analysis of the dataset to uncover patterns, trends, and insights. This included analyzing the distribution of sentiment labels, examining the most frequent words, and exploring any relationships between sentiment and other variables.

Data Visualization: We used various visualization techniques, such as bar plots, and sentiment distribution charts, to visually represent the data and gain further insights into the sentiment patterns.

## Project Overview
The objective of this project is to develop a sentiment analysis model that can accurately classify customer reviews into positive, negative, or neutral sentiment categories. The model aims to automate the process of sentiment classification, enabling businesses to quickly understand customer sentiment at scale.
To achieve this, we implemented the following steps:
1. Data Preparation: We split the dataset into training and testing sets to evaluate the performance of our model. We used X% of the data for training and Y% for testing.
2. Feature Extraction: We applied various techniques such as bag-of-words, count vectorizer 
3. Model Selection: We experimented with different algorithms, such as logistic regression, support vector machines, or neural networks, to determine the best-performing model for sentiment analysis. We evaluated the models using appropriate evaluation metrics such as accuracy, precision, recall, and F1 score.
4.Model Training and Evaluation: We trained the selected model on the training data and evaluated its performance on the testing data. We fine-tuned the model parameters to optimize its performance and prevent overfitting.
5. Model Deployment: Once we achieved satisfactory performance, we deployed the sentiment analysis model to make predictions on new, unseen customer reviews. We integrated the model into a user-friendly interface or API that can be accessed by stakeholders for real-time sentiment analysis.
By undertaking this project, we aim to provide businesses with valuable insights into customer sentiment, enabling them to make data-driven decisions, improve customer satisfaction, and enhance their overall brand reputation.
Please note that the above example is just a brief illustration, and you should customize it according to your specific project requirements and scope.

Methodology
Data Preprocessing: We performed data cleaning and preprocessing steps such as removing special characters, stopwords, and performing tokenization. We also applied lemmatization using NLTK's lemmatizer to reduce words to their common root form.

Vectorization Techniques:
a. Bag-of-Words (CountVectorizer): We used sklearn's CountVectorizer to convert the text data into a numerical representation, capturing the frequency of words in each document. This approach creates a matrix of word counts.

b. Classification Models: We trained and evaluated several classification models using the vectorized data, including:

1.Logistic Regression Classifier for the binary classifier model
2.Multinomial Naive Bayes and XGBoost model for the multiclass classification model 

c. Model Evaluation: For each model, we employed cross-validation techniques to assess its performance. We measured key evaluation metrics such as accuracy, precision, recall, and F1 score to evaluate the model's ability to correctly predict sentiment.

d. Handling Class Imbalance: As sentiment analysis datasets often suffer from class imbalance, we addressed this issue by employing techniques such as oversampling the minority class using Synthetic Minority Random Under-sampling

e. resample of XGBoost (add this from notebook)


# Evaluation
To evaluate the performance of our NLP sentiment analysis model, we conducted thorough testing and analysis using various evaluation metrics. The following evaluation results provide insights into the effectiveness of our approach:
* Accuracy:
1. Our binary sentiment analysis model achieved an overall accuracy of 90% which surpused our trget of achieving 85%.
2. our MultinomialNb multiclass model achieved an overall accuracy of
3. our XGboost multiclass model achieved an overall accuracy of 


![image](https://github.com/Daniel1999Akama/moringa_phase4_project/assets/96378206/158e9d2a-3fe3-4f45-ab69-3831220f3aae)

No emotion towards brand had the highest value count 

# Conclusion
In summary, our NLP model for Twitter sentiment analysis of Apple and Google products provides valuable insights for businesses. It categorizes sentiments as positive, negative, or neutral, helping understand public perception, monitor customer satisfaction, and make informed business decisions.The binary logisitc regression model performs best and is fit to be deployed.
​
# Recommendations

Overall, this project demonstrates the potential of sentiment analysis in extracting valuable insights from textual data. By understanding the sentiment expressed in text, businesses and organizations can make informed decisions, gain customer feedback, and enhance their understanding of user opinions and preferences.

# Nextsteps
1. In our future work, we plan to explore advanced techniques such as incorporating attention mechanisms, using ensemble methods to further enhance the model's performance by incorporating domain-specific and fine-tuning the model on industry-specific datasets could improve its accuracy and adaptability.
2. By considering these evaluation metrics, addressing limitations, and planning for future improvements, we aim to develop a robust NLP sentiment analysis solution that effectively captures sentiment in text data.
3. Looking for a better dataset 


# Limitaion


# Installations
To install and run this project, follow these steps:
1. Clone the repository to your local machine using the following command:
    - git clone https://github.com/Daniel1999Akama/moringa_phase4_project.git
2. Navigate to the project's root directory:
    - cd your-repository
3. Install the project dependencies(For this project we worked with Jupyter notebook, however it can also run on vscode or Google collab:
    - This command will install all the necessary packages and libraries required for the project to run(this should br run in the terminal(for our case Anaconda).
    - pip install Jupyter Notebook 
5. Call the note book in the directory
    - jupyter notebook
    - code .. for VS code
6. Open your web browser and access the application at http://localhost:5000.
    This is the default URL where the application will be running locally. 

### Collaborators
feel free  to visit this jupyternotebook and contact below emails


Rosemary Nyakio: @nyakio19roseary@gmail.com

Maureen Anduuru: @moesaitia@gmail.com

Daniel Akama: @danielakama23@gmail.com

Leah Katiwa: @katiwaleah26@gmail.com

Lynne mutwiri: @mutwirilyneek@gmail.com

Brian Nderu: @briannga00@gmail.com



### Repository Structure: 

├── .gitignore                                              

├── CONTRIBUTING                                            

├── LISENCE.md                                             

|── Phase4_project.ipynb                                   

├── data                                                   

├── README.md                                             



