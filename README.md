# CyberBullying-Recognition
If a tweet is indeed a cyberbullying tweet, we'll go even further and predict its nature, classifying it into six intriguing categories:

1. Age
2. Ethnicity
3. Gender
4. Religion
5. Other Cyberbullying
6. Miscellaneous

we'll be utilizing the Cyberbullying Classification dataset from Kaggle, a treasure trove of valuable information (you can find it here: https://lnkd.in/d7pfHGT8).

Now, let's unravel our approach step by step, keeping it simple and straightforward:

1. Installation and Data Import: We'll start by installing the necessary libraries and importing the dataset using the powerful pandas library, setting the stage for our analysis.

2. Data Check: A preliminary review of the dataset will be conducted to ensure that we have a clear understanding of its contents and to identify any missing values.

3. Text Preprocessing: Brace yourself for some text transformation magic! We'll perform a series of preprocessing steps to clean up the text, including:
   - Removing emojis
   - Converting text to lowercase
   - Eliminating unwanted characters like line breaks, URLs, non-UTF characters, numbers, and punctuation
   - Filtering out common stopwords
   - Handling contractions
   - Cleaning up hashtags
   - Filtering special characters
   - Removing excessive whitespace
   - Applying stemming and lemmatization techniques

4. Duplicate Handling: We'll ensure the integrity of our data by identifying and removing any duplicate entries.

5. Exploratory Data Analysis: Prepare to be amazed as we explore the depths of our dataset, uncovering fascinating insights and patterns along the way.

6. Train and Test Split: To train and evaluate our models effectively, we'll split the dataset into training and testing subsets, ensuring accurate predictions.

7. tf-idf Vectorization: We'll transform the text into numerical vectors using the powerful tf-idf technique, a crucial step in machine learning text analysis.

8. Base Models Exploration: Get ready for a thrilling model comparison! We'll experiment with various base models, including:
   - Logistic Regression
   - Support Vector Classifier
   - Naive Bayes Classifier
   - Decision Tree Classifier
   - Random Forest Classifier
   - Ada Boost Classifier

9. Fine-Tuning: Our quest for the ultimate model doesn't end there! We'll fine-tune the Support Vector Classifier to squeeze out every last drop of performance.

10. Model Evaluation and Saving: We'll carefully evaluate the performance of our models, selecting the best-performing one and saving it for future use.

11. Web App Creation: Prepare to be dazzled by our technological prowess! We'll create an interactive web app using Streamlit, making it easy to explore and experience our models firsthand.

12. Web App Deployment: We'll take our web app live by deploying it on Streamlit, allowing anyone, anywhere to access and benefit from our groundbreaking analysis.

we'll make use of several powerful libraries, including pandas, numpy, matplotlib, seaborn, stats, scipy, re, pickle, string, image, collections, statsmodel, flask, nltk, emoji, wordcloud, and, of course, Streamlit. These tools will be our trusted companions on this thrilling journey.

