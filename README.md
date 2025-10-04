# VentBuddy : A Data-Driven Companion for Mental Health Support

## Project Overview  
Mental health is a growing concern in today’s digital age. This project explores mental health discourse using the **Reddit Mental Health Dataset (RMHD)**, which contains anonymous posts from users who self identify with conditions such as depression, anxiety, and burnout.  

We will follow the full data science pipeline:  
- Data acquisition and preprocessing  
- Exploratory Data Analysis (EDA)  
- Sentiment analysis and hypothesis testing  
- Multi-class classification of mental health conditions  
- Development of VentBuddy, a Streamlit-based chatbot that allows users to vent their emotions and thoughts, predicts their emotional state, and responds with supportive messages.  
---

## Group Members  
- Venkata Sai Sri Pujya Kothapalli – 121985248  
- Venkata Sai Pradyumna Nadella    – 122096059  
- Mridhula Senthilkumar            – 121944900  
---

## Dataset Information  
- **Dataset**: [Reddit Mental Health Dataset (RMHD)](https://www.kaggle.com/datasets/entenam/reddit-mental-health-dataset)  
- **Source**: Reddit posts from users who explicitly self-identified with mental health conditions  
- **Size**: ~350,000 posts (~1.68GB zipped)  
- **Key Columns**:  
  - `author` – User identifier (anonymized)  
  - `subreddit` – Source subreddit  
  - `title` – Title of the post  
  - `post` – Body text of the post  
  - `label` – Assigned mental health condition (e.g., depression, anxiety, burnout)  
  - `timestamp` – Date/time of the post  
---

## Why This Dataset  
We chose this dataset because:  
- It provides **authentic** data from the individual.  
- It is large and diverse, allowing for robust **NLP and classification analysis**.  
- The labeled conditions enable building models that classify posts into **mental health categories**.
---

## Project Topic  
- Natural Language Processing (NLP)  
- Text Classification (Multiclass)  
- Sentiment Analysis
