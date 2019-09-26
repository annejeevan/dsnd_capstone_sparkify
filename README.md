# Predict Customer Churn
--------------------------------------
1. [Installation](#installation)
2. [Project Motivation](#motivation)
3. [File Descriptions](#files)
4. [Results - Blog Post ](#results)
5. [Conclusion](#conclusion)
6. [Licensing, Authors, and Acknowledgements](#licensing)

## 1. Installation <a name="installation"></a>
- Pandas
- Numpy
- pyspark sql & ml
- Sklearn
- Seaborn
- Matplotlib etc.,
- The code should run with no issues using Python versions 3.*.

## 2. Project Motivation <a name="motivation"></a>
For this project, I was interestested in predicting the customer churn and helps the company to offer discounts

Determine customer churn for a music streaming company called Sparkify. The users stream their favorite songs either using the free tier that place advertisements between songs or use the premium plan for which they pay a monthly fee with no advertisements between songs. Users can upgrade, downgrade or cancel their services. The dataset given to us contains a log of the activities of each user on the service whether they are playing songs, logging out, upgrading their service or cancelling the service. All this data contains key insights in keeping the users of the service happy. Our task in this project is to develop a model that predict which users are at risk. If we can identify users that are at risk to churn either by downgrading from premium or by cancelling their service, the business can offer them incentives and discounts potentially saving millions in revenues or maximize revenues.

Also, to use the Apache Spark in performing ETL operations and prepare the data for building machine learning models, which is a scalable way to parse through the large files.

## 3. File Descriptions <a name="files"></a>  
- gender.png: Distribution of Gender against the Churned/ Not Churned users
- level.png and level1.png: Distribution of level (Free or Paid) against the Churned/ Not Churned users
- page.png: Distribution of the pages users navigated
- top15.png: Distribution of the artists users listen 
- blog.md: Blog post on github related to the analysis

To walk-thru the full project, check out the [notebook](Sparkify.ipynb).
Markdown cells were used to assist in walking through the thought process for individual steps.  

## 4. Results - Blog Post <a name="results"></a>
The main findings of the code can be found at the post available [here](blog.md).

Also, shared my insights on [Medium](https://medium.com/@jeevananandanne/predicting-churn-of-customers-423461439422)

## 5. Conclusion <a name="conclusion"></a>
We looked at Sparkify users transaction data to predict the churn of a user. There were some useful insights found at each part of our questions, but equally there were some questions left unanswered. 

Three high level takeaways include:

- Sparkify users appear to use more free subscriptions, and cancel the subscription when free subscription ends
- Surprisingly paid users listen to the songs more than free users
- Simple and faster model, Random Forest seemed to perform well, with proper cross validation (for tuning parameters)

## 6. Licensing, Authors, Acknowledgements<a name="licensing"></a>
Credits to 
  -  Udacity
  -  AWS 
  -  https://spark.apache.org/docs/2.1.1/mllib-linear-methods.html#logistic-regression


