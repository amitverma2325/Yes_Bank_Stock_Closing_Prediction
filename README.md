                                             YES_BANK_STOCK_PRICE_PREDICTION






![proj_4](https://github.com/amitverma2325/Yes_Bank_Stock_Closing_Prediction/assets/159435374/41cd8f17-40e7-43d1-b28d-7f043d4229fe)


                                             
  
Regression Capstone Project Yes Bank stock price prediction

Project Summary:

Yes Bank is a banking company that was founded in 2004 that offers a wide range of differentiated products for its corporate and retail customers through retail banking and asset management services. It is also a publically traded company. That provides an opportunity for anyone to invest in Yes bank and become a shareholder. But at the same time, it means that the valuation of the company is now in the hands of investors and speculators as share prices are often heavily impacted by public opinion. We have used yes bank stock price data set. This dataset contains 5 different features that can be used for predicting close price prediction using machine learning.

In this project i have applied three different model and check the performance of each model through different metrics and findind the best one from it.

This project involve follwing steps.

Firstally i have dealt with cleaning and preprocessing of the data removing inconcistencies from the data like checking null values duplicates and handling null values and dropping irrelevant data these all steps comes under Data Wrangling.

Secondally we do Visualization of varibles through different chart and then done hypotheses testing,feature engineering.

In the third part i applied three different model namely Linear Regression,Random Forest Regressor and XGBoost Regressor and check performance of metrics through these models.

The project concludes that Linear Regression is best model according to other models in term of R2 score.

Overall, the project aimed to contribute to a better understanding of the relationship between the fraud case and Yes Bank's stock prices, and to explore the potential of predictive models in the financial domain. The findings and insights gained from this project can be utilized by investors, analysts, and decision-makers to make informed investment or business decisions related to Yes Bank's stock.

Conclusion:

The main goal of the project is to create a machine learning model which can predict the closing price of Yes Bank stock for that month, keeping in mind of the fraud case happened in 2018.

Using data visualization on our target variable, we can clearly see the impact of 2018 fraud case involving Rana Kapoor as the stock prices decline dramatically during that period.

All the variables in the dataset are positively skewed and we applied log transormation to make them normally distributed

I have developed three model:


*   Linear Regression
*   Random Forest Regressor
*   XGBoost Regressor

Found the most suitable basic Linear Regression model with highest R2 score as compared to other model.

Given the dataset and features, Our model is performing well on all data-points. With our model making predictions with such high accuracy, we can confidently deploy this model for further predictive tasks using future data.
