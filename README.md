# 🍔 FoodPanda Sentiment Analysis (Google Reviews)

## Introduction

<p align="justify">
Launched in Singapore in 2014, foodpanda is a food delivery platform owned by Delivery Hero. Dedicated to providing customers with fast service, foodpanda has quickly grown its presence in over 400 cities across 11 markets in Asia, including Singapore, Hong Kong, Thailand, and Malaysia.
Powered by technology and operational excellence, foodpanda now serves millions of customers with a convenient way to get food and groceries delivered in just a few taps, thanks to its reliable partners, riders, and a team united by shared values.

</p>

## Background

<p align="justify">
An avid pandapro user, I have been subscribed to Foodpanda's monthly subscription ever since the gruesome lockdown days. 
  If I am being honest, I probably spent a ton on food deliveries between 2020-2022 😪 This project was therefore created to look through at the sentiments of the organization's users! In this project, I delved into natural language processing (NLP) methods to analyze the user feedback and pinpoint both areas of dissatisfaction and features that are highly valued within the app, while also exploring additional insights.
</p>

<p align="justify">
The findings were intended to inform meaningful suggestions for Foodpanda, such as enhancing service consistency, streamlining processes, improving customer support, and fostering positive rider interactions. The project sought to leverage valuable user feedback to guide the organization's product development and customer retention strategies.
</p>

<p align="justify">
Additionally I used the DistilBERT sentiment analysis model to correctly identify positive and negative reviews, reflecting to the actual sentiment of Foodpanda's users.
The confusion matrix then revealed the model performed better at identifying positive reviews compared to negative ones, suggesting potential biases or limitations. 
This insight highlighted the need to further investigate the model's performance and explore alternative approaches for more balanced and accurate sentiment classification.
</p>

Do take a look at the full analysis <a href='https://github.com/ghazi-hishamuddin/FoodPanda-Sentiment-Analysis/blob/main/foodpanda_sentimentanalysis.ipynb'>here</a>! 
## Dataset

<p align="justify">
The dataset is obtained from Kaggle (https://www.kaggle.com/datasets/bwandowando/foodpanda-app-reviews-from-google-store), with over 500,000 Google reviews from 2013. An amazing dataset to look through sentiment trends!
</p>

## Libraries Used
+ Pandas
+ Numpy
+ NLTK
+ HuggingFace 🤗

<hr>

# The Analysis
1. 
![image](https://github.com/ghazi-hishamuddin/FoodPanda-Sentiment-Analysis/assets/142828521/8787effc-1e24-403e-a342-8915e8e1bbb3)

2.
![image](https://github.com/ghazi-hishamuddin/FoodPanda-Sentiment-Analysis/assets/142828521/dda16e7e-784b-41a5-9677-7622bf707062)

3.
![image](https://github.com/ghazi-hishamuddin/FoodPanda-Sentiment-Analysis/assets/142828521/6455fc17-97ab-4974-bc99-7fc54a95019b)

4.
![image](https://github.com/ghazi-hishamuddin/FoodPanda-Sentiment-Analysis/assets/142828521/7cbccff4-071e-443d-a31b-799830b7ad62)

<table border="1" cellspacing="0" cellpadding="5">
  <thead>
    <tr>
      <th>Class</th>
      <th>Precision</th>
      <th>Recall</th>
      <th>F1-score</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>👎 Negative</td>
      <td>0.906</td>
      <td>0.676</td>
      <td>0.774</td>
    </tr>
    <tr>
      <td>👍 Positive</td>
      <td>0.784</td>
      <td>0.944</td>
      <td>0.856</td>
    </tr>
    <tr>
      <td>📊 Overall Accuracy</td>
      <td>0.824</td>
      <td>-</td>
      <td>-</td>
    </tr>
  </tbody>
</table>

5.
![image](https://github.com/ghazi-hishamuddin/FoodPanda-Sentiment-Analysis/assets/142828521/6769a4d4-60e0-426d-8f17-5602fcf29dd5)

<table border="1" cellspacing="0" cellpadding="5">
  <thead>
    <tr>
      <th>Class</th>
      <th>Precision</th>
      <th>Recall</th>
      <th>F1-score</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>👎 Negative</td>
      <td>0.904</td>
      <td>0.710</td>
      <td>0.795</td>
    </tr>
    <tr>
      <td>👍 Positive</td>
      <td>0.816</td>
      <td>0.945</td>
      <td>0.876</td>
    </tr>
    <tr>
      <td>📊 Overall Accuracy</td>
      <td>0.846</td>
      <td>-</td>
      <td>-</td>
    </tr>
  </tbody>
</table>



<hr>

## Concluding Remarks:
<p align="justify">
</p>
