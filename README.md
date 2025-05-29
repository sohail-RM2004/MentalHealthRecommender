# MentalHealthRecommender
Mental Health Wellness Chatbot Recommender System --purely NLP based--

This a context-aware mental health chatbot made using Python, Scikit-learn, and NLTK to classify user emotions from self-written text using TF-IDF and classical ML models (SVM, Logistic Regression, Naive Bayes).

The Model achieved accurate multi-class emotion prediction (e.g., sadness, joy, anger) by training on labeled emotional datasets with preprocessing (tokenization, lemmatization, stopword removal).

It works as a personalized recommendation system providing therapeutic resources: quotes, articles, exercise routines, yoga videos, and supportive conversation, mapped to each predicted emotion.

It is deployed as an interactive terminal-based chatbot with modular components for real-time text input, mood analysis, and contextual feedback using a trained model pipeline.

I have serialized model (joblib) with TF-IDF vectorizer and label encoder for scalable reuse.
