# DTSA-5509-Supervised-Learning-Final-Project---Big-Data-Derby-2022
    Summary: 
    2019 Horse Derby race data. Using this data, I can create an analysis and produce models that help myself 
    and others understand what attributes associated with the horse derby races may correlate with or  
    predict the outcome of the race. Using my Python knowledge and machine learning concepts, I can ingest
    this data, clean it, visualize it, and produce conclusions using varying tools. 
    
    Goal: 
    The basic idea behind this whole project is to develop a better understanding of different 
    strategies related to the overall competition.

    Conclusion:

Based on numerous regression models we can see that if the desire to predict or estimate the position at
the finish of a race, it is crucial to maintain two features: race number and odds. These two features had the strongest 
correlation from the start based on the heatmap and matrix. 

Fine-tuning the data and analysis, I was able to compare and contrast using linear/multi-linear regression models
with polynomial regression models. Further analysis through forward stepwise refinement, 
I was able to confirm that odds and race number were the two main features to be added to the predictive model
for the data.In addition, by plotting the forward stepwise refinement models, 
plotting R-squared values against the number of features/predictors, 
it was clear that the two features will maintain close to the strongest correlation between the features without the risk of 
overfitting or using too many features, that could have colinearity or the like. 

Through the comparison and contrast of the regression models, I can see that the polynomial model provided a 
better predictive model. The polynomial model outputted a stronger and higher R-squared value, 
but to back this conclusion, the RMSE, MSE, and MAE scores were found and proved that the polynomial regression model 
resulted in a lower error score based on all three formulas. Found that by using the polynomial regression model, 
the best degree to use with the two main features to predict POF was that it did its best with a degree of 4. 
This proved to provide the strongest R-squared value and again the lowest error score for all three tests. 

However, from the start and even after building a stronger predictive model, the R-squared value proved to be smaller
and only came out to be closer to 0.30s. This still does not guarantee a very strong relationship between the feature's 
odds and race number with the position at the finish. But based on the data provide and proper analysis and deduction, 
it seems to have provided the best relationship I could have created and outputted based on the knowledge I had on this 
data and from my education. 

I assume many tasks could be performed to continually improve the performance of the models
I mentioned above. Although, my goal was to get a better understanding of this data and help provide more insight into
the predictive nature in the realm of derby horse racing. Now know what attributes of the 
derby have some impact on the overall results of the race, and can continue to work on these models to ideally create
an even stronger model to predict the overall standings of each race for each competitor/animal/jockey.
​
Citations:

Data is obtained from the Kaggle website through the Big Data Derby 2022 analytics competition. 
URL: https://www.kaggle.com/competitions/big-data-derby-2022/dataUploading 
Using the nyra_2019_complete.csv, that is the complete 2019 derby data, that contains all three tables.

End of notebook Track visuals - Original work was completed by MATT OP, Big Data Derby 2022 EDA. 
Citing URL: https://www.kaggle.com/code/mattop/big-data-derby-2022-eda
