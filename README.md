# Gold-Loan-Prediction-by-machine-learning-Random-forest

Gold is  one of  the critical commodities  that  is used  as a barometer of  economic activity prevailing in  the globalized world. The price  of the gold is  dependent on many economic indicators and is complex to understand the dynamics of its price discovery. To predict the prices  of gold  is paramount  for  any  business  involved in  global trade  and in  turn  gives indications of the overall financial stability of the global business environment. In this project, a system which is based on machine learning algorithms to predict the gold prices based on the historical data related to other closely related commodities and stock market indicators. The system is based on Random Forest Regression algorithm which is used to train on historical commodity prices such as Crude oil, Silver Price, Stock Price which are key indicators  of  the  global  financial  markets  and  forms  the  core  decision  logic  for  future predictions. The results prove that the Random Forest Regressor Machine learning Algorithm performs better than the other methods with a forecasting accuracy of 98%.

# A Brief about Random Forest Regression-
A simple yet crisp definition, to understand what Random Forest Regression Algorithm is, will be, “Random Forest Regression is a supervised learning algorithm that uses ensemble learning method for regression. It operates by constructing several decision trees during training time and outputting the mean of the classes as the prediction of all the trees“

The flow-chart depicting Random Forest Algorithm is shown below-
![70579Screenshot (152)](https://user-images.githubusercontent.com/115232340/198563378-71ec4754-c0f6-400b-ab5b-2fe4f32c5fee.png)

# Work Flow-
<img width="744" alt="96433Screenshot (153)" src="https://user-images.githubusercontent.com/115232340/198563606-61d0bb77-375a-4faf-be27-31eb93343968.png">

# What is a Dataset-
In this project, I have used the dataset available on Kaggle. One can find various such sites to download from. (Note that the larger the dataset, the more time the model will take to train. As a beginner-friendly suggestion, I will tell you to take a medium-sized dataset with not too many values, to first understand its working. The dataset that I’ve used in my code was the data available on Kaggle. You can also download it here. Although, you must also know, the more data you feed to the model for training, the more we can train our model, and the more accurate our results come out to be, but also, at the same time, the compilation time increases, and if you are a beginner, you may lose your enthusiasm in that tedious times. Don’t worry if all of this sounds weird to you, it did the same to me when I started too, it will all make sense in a few minutes.

# Steps-
1. Import Libraries
2. Import Data'
3. Convert datatype of date column
4. Check Null values
5. Statistics of dataset
6. Data Visualization
7. Define Dependent and Independent variables
8. Split training and testing dataset and fit
9. Check accuracy
10. Prediction

# First 5 rows of dataset-
![5 rows ](https://user-images.githubusercontent.com/115232340/198569391-3be2ac20-4968-4f29-b701-b360428d2408.png)

# Pairplot of dataset-
![pairplot](https://user-images.githubusercontent.com/115232340/198569497-16e5e6a4-8e3d-4e94-9e74-315d53859e98.png)

# Lineplot of all variables with date-
![all columns](https://user-images.githubusercontent.com/115232340/198569559-ac75f6ee-0bb3-44d5-8611-1a631d12670d.png)

# Correlation of each variables with other-
![corr heatmap](https://user-images.githubusercontent.com/115232340/198569587-abe04893-5964-4f89-8947-da78f4323120.png)

#  Actual Gold Price vs Predicted Gold Price
![act vs pred](https://user-images.githubusercontent.com/115232340/198569615-99c44178-37c9-487d-961d-cd213810a957.png)

# Power BI report-
![power bi](https://user-images.githubusercontent.com/115232340/198571992-48d16c9d-3dac-4f93-a558-14c571ab15b2.png)

# Conclusion- 
As you saw in this project, we first train a machine learning model, then use the trained model for prediction. Similarly, any model can be made much more precise, by feeding a very large dataset, to get a very accurate score (but it will be pretty time-consuming). For a beginner, I feel the dataset that I had used was pretty decent.

Thanks for reading…

If you liked the article, do share it with your friends too.

Have a good day..!!
