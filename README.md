## Calexise
Repo for my small Healthcare Data science application which can predict the calorie burned during workout.

#### Let me brief the steps I did for this projects:

* **Ideation**: While doing my regular workout as usual, I got intrigued by the idea if I can pricisely customize my workout on the basis of how many calories I am burning in my exercises. So I started thinking about the same. Though I am very well aware of smartbands and smartwatches available in the market which can really solve my problem, but geek inside me got excited about exploring how this thing works inside smartbands and if I can produce the near estimate result myself for the same.
* **Data collection**: I was lucky enough to find the relevant dataset as per my need on the kaggke itself, so it worked out for me.
* **Analysis of data**: Next comes the data analysis part, since it was multi feature dataset, so needed proper attention(data just need attention, else will speak out itself).
Did basic analysis like description of data, null(Nan) values, correlation, plots, etc.
* **Model creation**: Here I used simple linear regression by selecting the most relevant features and also did multiple linear regression by using all the features. Also tried polynomial multiple linear regression for better accuracy.
* **Evaluation**: Now came the model evaluation part. This part was all concerned about training, testing, error evaluation, r squared calculation, error optimization, etc.
* **Deployment**: After properly training and testing the model, I used streamlit to design an interactive front end for the model and deployed it using the same.

For in depth knowledge of each and every step please refer to the attached .ipynb file and .py file
