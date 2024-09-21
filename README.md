# About me
Highly motivated IT professional with a background in QA Test Analysis and a strong foundation in SQL. Recently graduated with a Master of IT in Business, looking to transition into a Data Science role. Seeking to leverage both technical and business acumen to optimize data processes and contribute to the efficiency of data-driven decision-making in a dynamic organization.
## TeePublic Customer Review Analysis: Topic Modeling and Sentiment Analysis
This project focuses on analyzing over 250,000 customer reviews from TeePublic, a prominent e-commerce fashion platform. The goal is to extract valuable insights from the data to improve customer experience and inform business strategies.

### Motivation
Understanding customer feedback is essential for optimizing user experience, identifying satisfaction drivers, and detecting market trends. This project aims to:

Discover key topics in customer reviews.
Explore topic variation across different regions.
Build predictive models to classify future reviews by sentiment.
### Objectives
Topic Modeling: Uncover topics from customer feedback using LDA (Latent Dirichlet Allocation).
Sentiment Analysis: Build a Naïve Bayes classifier to categorize reviews as positive, negative, or neutral.
Regional Insights: Compare customer feedback topics by location.
### Workflow
Data Preprocessing:
Derive columns like ratings and regions.
Merge titles with review text.
Clean data by removing special characters, punctuation, and stop-words (with an extended list).
Stem words to simplify variations.
Topic Modeling:
Generate a word cloud to visualize frequently discussed topics, which show a strong presence of positive feedback.
Apply LDA models using both Gensim and Sklearn libraries to extract latent topics. We use a 10-topic configuration and compare models based on coherence and perplexity scores.
Sentiment Analysis:
Classify reviews using Naïve Bayes and Random Forest models.
Classify reviews as "good," "bad," or "neutral" based on the sentiment score.
### Results
The project provided a deep dive into customer feedback, revealing key areas for improvement. It showcased the strength of positive comments while pinpointing regions for further analysis. Topic modeling using LDA gave actionable insights into customer emotions, while sentiment analysis helped in identifying patterns of satisfaction and dissatisfaction.
