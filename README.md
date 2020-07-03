# M5-Series-Accuracy

This repository contains code for solving the problem mentioned in https://www.kaggle.com/c/m5-forecasting-accuracy.

This was my first attempt at solving a time series forecasting problem. This problem consisted of predicting the sales for **Walmart Retail** for a **period of 28 days**.
The task was concentrated in the United States across **10 stores** in CA, TX and WI. The sales were further divided into **7 departments** and **3 categories**. 

A number of important features were learnt during the course of this project:

- Melting a Pandas dataframe, used in this project to convert the column headers into individual row elements
- Introducing lag features and rolling average of the different lag features on some window
- Using **LightGBM** to handle extremely large datasets

Finally the result was a **rank of 861/5558 teams** with a **WRMSSE score of 0.74986**. Although, it could have been better, the amount of learning in this competition was immense.
