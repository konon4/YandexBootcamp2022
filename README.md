<center><h1>Yandex.Practicum Data Science Bootcamp 2022</h1></center>

![Practicum Bootcamp](pb.png "Practicum Bootcamp")

## 1_yandex_music_hypothesis_testing.ipynb

### Hypothesis testing

The comparison between Moscow and St. Petersburg is surrounded by myths:
Moscow is a megalopolis subject to the rigid rhythm of the work week;
St. Petersburg is a city of peculiar culture, unlike Moscow.
Some myths reflect reality. Others are empty stereotypes. Business must distinguish the former from the latter in order to make rational decisions. Using real data from Yandex Music you will test the hypotheses and compare the behaviour of users of the two capitals.

#### Hypotheses
1. The activity of users depends on the day of the week. And in Moscow and St. Petersburg it manifests itself differently.
2. On Monday morning in Moscow some genres of music prevail, and in St. Petersburg - others. This is also true for Friday evening.
3. Moscow and St. Petersburg prefer different genres of music. In Moscow they listen to pop music more often, in St. Petersburg they listen to Russian rap music.

## 02.1_borrower_reliability_study
## 02.2_borrower_reliability_study

### Borrower reliability study

The client is the credit department of the bank. We need to understand whether the marital status and number of children of the client affects the fact of repayment of the loan on time. Input data from the bank - statistics on the solvency of customers.
The results of the study will be taken into account when building a credit scoring model - a special system that evaluates the potential borrower's ability to repay the loan to the bank.

## 3_exploratory_data_analysis.ipynb

### Exploratory data analysis

You have at your disposal the data of Yandex Real Estate - an archive of ads for several years on the sale of apartments in St. Petersburg and neighboring localities.
Your task is to pre-process the data and study them to find interesting features and dependencies that exist on the real estate market.
There are two types of data in the database about each apartment: user-added data and cartographic data. For example, the first type includes the area of the apartment, its floor and the number of balconies; the second type includes distances to the city center, the airport and the nearest park.

## 4_statistical_data_analysis.ipynb

### Statistical analysis of data

You are an analyst at "Megaline", a federal cellular operator. Clients are offered two tariff plans: "Smart" and "Ultra". In order to adjust the advertising budget, the commercial department wants to understand which plan brings in the most money.
You will do a preliminary analysis of the tariffs on a small sample of customers. You have the data of 500 "Megaline" users at your disposal: who they are, where they come from, what tariff they use, how many calls and messages each sent in 2018. You need to analyze customer behavior and draw a conclusion - which tariff is better.

## 5_game_success_prediction.ipynb

### Predicting game success

Historical data on game sales, user and expert evaluations, genres and platforms (e.g. Xbox or PlayStation) are available from open sources. You need to identify the patterns that determine a game's success. This will allow you to bet on a potentially popular product and plan advertising campaigns.

## 7_bank_customer_loss_prediction.ipynb

### Bank customer loss prediction

Clients began to leave "Beta Bank". Every month. Not much, but noticeable. Bank marketers have calculated: it's cheaper to keep current customers than to attract new ones.
You need to predict whether a client will leave the bank in the near future or not. You are provided with historical data on customer behavior and termination of contracts with the bank.
Construct a model with an extremely high value of F1-measure. You need to bring the metric to 0.59 in order to pass the project successfully. Test F1-measure on the test sample by yourself.
Additionally measure AUC-ROC, compare its value with F1-metric.

## 8_bootstrap_oil_production_region_selection.ipynb

### Choosing a location for the well

Let's say you work for an oil company. You have to decide where to drill a new well.
You are given oil samples from three regions: each has 10,000 oil fields where you have measured the quality of the oil and the volume of oil reserves. Build a machine learning model that will help you determine the region where production will bring the most profit. Analyze the possible profits and risks with Bootstrap.

## 9_gold_mining_prediction.ipynb

### Predicting the recovery rate of gold from gold-bearing ore.

The model should predict the recovery rate of gold from gold-bearing ore. You have data with mining and refining parameters at your disposal.
The model will help to optimize production so that you don't run a plant with unprofitable characteristics.

## 10_linear_algebra.ipynb

### Protection of Customers' Personal Data

You need to protect insurance company customer data. Develop a method of data conversion that makes it difficult to recover personal information. Justify the correctness of its operation.
You need to protect the data so that the quality of machine learning models does not degrade during conversion. There is no need to select the best model.

## 11_predicting_car_prices.ipynb

### Predicting car prices.

Service for the sale of used cars is developing an application to attract new customers. In it you will be able to find out the market value of your car.
Build a model that knows how to determine it. You have at your disposal data on the technical characteristics, equipment and prices of other cars.
The criteria that are important to the customer:
- the quality of the prediction;
- the learning time of the model;
- the prediction time of the model.

## 12_time_series_forecasting.ipynb

### Taxi Order Forecasting

The company collected historical data on cab orders at airports. To attract more drivers at peak times, you need to predict the number of cab orders for the next hour. Construct a model for this prediction.
The value of the RMSE metric on the test sample should be 48 or less.

## 13_NLP_classifying_toxic_comments.ipynb

### Identifying toxic comments

The online store is launching a new service. Now users can edit and add to product descriptions, just like in wiki communities. That is, clients propose their own edits and comment on the changes of others. The store needs a tool that will look for toxic comments and send them for moderation.
Train your model to classify comments into positive and negative. You have a data set with markup about the toxicity of edits.
Build a model with an F1 quality metric value of at least 0.75.

## 15_CV_customer_age_prediction.ipynb

### Predicting age by photo

The supermarket is implementing a computer vision system to process customer photos. Photo-fixing in the checkout area will help determine the age of customers in order to:
Analyze purchases and offer products that may be of interest to shoppers in this age group;
Control the integrity of cashiers when selling alcohol.
Build a model that determines the approximate age of a person from a photo. You have at your disposal a set of photos of people with an indication of their age.

## 16_graduation_project.ipynb

### Graduation project

In order to optimize production costs, the steel mill has decided to reduce electricity consumption during the steel processing phase. You have to build a model that predicts the temperature of the steel.
