# H-M-Recommender

## Project Scope
This project is about machine learning models were explored to solve the H&M Personalized Fashion Recommendations problem on the Kaggle data science competition (https://www.kaggle.com/c/h-and-m-personalized-fashion-recommendations/overview) for SFU CMPT310 class project. Transaction history, customer and article metadata, as well as article image data was provided for this competition, but a simplified dataset based on the available data was used for the purposes of this project. The models tested include Markov Process, Term-Frequency, and a custom algorithm that ranked weekly trends. Ensemble models of these algorithms were also tested. 

## Intro
H&M offers an extensive choice of online items, and to facilitate the shopping experience, recommendation systems are a crucial technology that allows customers to spend less time browsing for items by presenting to them directly the products they might be interested in. The problem of learning a customer’s preferences can be intractable due to the inexhaustible range of factors that may influence a customer’s decisions. As such, an apriori model of customer behaviour is impractical, if not impossible. Instead, using data of past purchase behaviour presents an efficient if imperfect model to use for making product predictions. This lends itself well to training unsupervised learning methods that can quickly adapt to nuanced patterns as they happen in real time. Among unsupervised learning techniques, clustering is one of the most powerful models used for recommendation systems. For example, items that are frequently purchased together imply some common feature between them, and a clustering model will allow those other items to be prioritized for recommendation when one of them is purchased. All the models we explore in this project will make use of some form of clustering model.

## Data
- Data was provided by H&M Group as a part of a Kaggle data science competition.
- Shortened the transaction history range to dates between 2020-04-24 and 2020-09-22 (5 months)
- Focused for customers of age 25.

## Prediction Models
- Markov process
- Exponentially-Weighted Term-Frequency vector product (EXP-TF)
- Trending prediction (Quotient ratio)

More details in the report
