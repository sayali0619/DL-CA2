
Twitter Hashtag Prediction

This is a group project for Continuous Assessment at DIEMS. We have built an interface that will predict a hashtag, related to given ‘text’ or ‘tweet’. Here, we have used 'Gradio' to create the interface. The Dataset we have used is self-made using the help of examples from different online sources.


Project Description


Dataset Overview 


1. Twitter Data: Collection of tweets, is in raw text format or pre-processed. Each tweet has various attributes, such as the tweet text and predicted hashtags.
2. Hashtags: The dataset include the hashtags associated with each tweet. These hashtags can be seen as labels or targets for the prediction task. The hashtags may represent various topics, events, or themes related to the tweets.
3. Metadata: Additional metadata about the tweets and users can be included in the dataset. This could include information like the number of followers, number of friends, user location, verified status, and other relevant details that might help in building predictive models. [Metadata is not mentioned in this project, but for additional representation we can use it]
4. Features: In addition to the raw tweet text, the dataset include engineered features that capture relevant information for the prediction task i.e., given tweet. These features have been extracted from the tweet text. For example, features include the presence of specific keywords, sentiment analysis scores, or the popularity of the user posting the tweet.
5. Train/Test Split: To evaluate the predictive models accurately, the dataset has been divided into training and testing subsets. Typically, a larger portion of the data is allocated for training the models, while a smaller portion is reserved for evaluating their performance.
6. Data Pre-processing: Based on the dataset, certain pre-processing steps has been applied. These could include removing duplicate tweets, handling missing data, cleaning text (e.g., removing stop words, special characters), normalizing hashtags, and other necessary steps to prepare the data for analysis.
7. Evaluation Metrics: The dataset might include ground truth labels or annotations for evaluating the performance of hashtag prediction models. Evaluation metrics such as precision, recall, R2/score, and Rmse or others may be calculated to measure the effectiveness of the models.
Features

Similarity to Popular Hashtags: The similarity of the hashtag to other popular or trending hashtags.
Historical Popularity: The historical popularity or usage frequency of the hashtag.



Process

- Collect a dataset of tweets with relevant metadata containing the hashtags of interest.
-Pre-process the tweet data by cleaning and normalizing the text.
Engineer features that capture important aspects of tweets, user interactions, and temporal patterns.
Train a machine learning model using the pre-processed data and selected features.
Evaluate the model's performance, fine-tune it if necessary, and deploy it for prediction in a production environment.

Dependencies

All you need is Google Collab and the required dataset to create this WebApp on your device.


