## Zomato-Restaurant-Clustering-and-Sentiment-Analysis
![Zomato](https://user-images.githubusercontent.com/100950560/190726519-331d1e3d-b768-4248-b032-f2c3030a1474.jpg)
## AlmaBetter Verified Project
# Problem Statement and Project Description
Zomato is an Indian restaurant aggregator and food delivery start-up founded by Deepinder Goyal and Pankaj Chaddah in 2008. Zomato provides information, menus and user-reviews of restaurants, and also has food delivery options from partner restaurants in select cities.
The Project focuses on Customers and Company, you have to analyze the sentiments of the reviews given by the customer in the data and make some useful conclusions in the form of Visualizations. Also, cluster the zomato restaurants into different segments. The data is visualized as it becomes easy to analyze data at instant. The Analysis also solves some of the business cases that can directly help the customers finding the Best restaurant in their locality and for the company to grow up and work on the fields they are currently lagging in.
This could help in clustering the restaurants into segments. Also the data has valuable information around cuisine and costing which can be used in cost vs. benefit analysis
Data could be used for sentiment analysis. Also the metadata of reviewers can be used for identifying the critics in the industry.


India is well-known for its unique multi-food cuisine, which is offered in a huge number of restaurants and hotel resorts and symbolizes unity in variety. In India, the restaurant industry is changing rapidly. More People are appealing to the concept of eating restaurant meals, whether they dine outside or have food delivered to their homes. The increasing number of restaurants in every Indian state has encouraged an analysis of the information to gain some insights, noteworthy facts, and statistics about the Indian food sector. 

As a result, the purpose of this study is to analyze Zomato restaurant data in Hyderabad. Zomato is a restaurant aggregator and food delivery service based in India. With the use of unsupervised and supervised machine learning algorithms, the work here clusters restaurants into distinct segments and evaluates the sentiments in customer reviews. The analysis also resolves several business cases that can directly assist customers in locating the best restaurant in their area, as well as the company's growth and development in areas where it is currently underperforming.
## This project contains an executable file, a technical document and a presentation

## Attribute Information
## Use this dataset for clustering part

1.Name : Name of Restaurants

2.Links : URL Links of Restaurants

3.Cost : Per person estimated Cost of dining

4.Collection : Tagging of Restaurants w.r.t. Zomato categories

5.Cuisines : Cuisines served by Restaurants

6.Timings : Restaurant Timings

## Zomato Restaurant reviews
## Merge this dataset with Names and Matadata and then use for sentiment analysis part

1.Restaurant : Name of the Restaurant

2.Reviewer : Name of the Reviewer

3.Review : Review Text

4.Rating : Rating Provided by Reviewer

5.MetaData : Reviewer Metadata - No. of Reviews and followers

6.Time: Date and Time of Review

7.Pictures : No. of pictures posted with review

## Data Cleaning and Preprocessing
## Feature Engineering

Feature engineering is the process of selecting, manipulating, and transforming raw data into meaningful numerical features that can be used by machine learning algorithms.
## Zomato Restaurant names and Metadata

First, the restaurants dataset has columns such as Links, Cuisine, and Timings which aren't directly interpretable. The location of the restaurant can be extracted by the Links column. Cuisines can be clubbed and categorized into a few categories and a total number of cuisines served by a particular restaurant. Timings can be categorized into three categories to make analysis a little simpler.
## Exploratory Data Analysis

Exploratory data analysis is a crucial part of data analysis. It involves exploring and analyzing the dataset given to find patterns, trends and conclusions to make better decisions related to the data, often using statistical graphics and other data visualization tools to summarize the results. Python libraries like pandas are used to explore the data and matplotlib and seaborn to visualize it.

Some important aspects to include in the project are as follows:

Best restaurants in the city

The Most Popular Cuisines in Hyderabad

Restaurants and their Costs

Cost-Benefit Analysis

Hypotheses Generation on visualized data for Clustering

## Best Restaurants in the City

There are various factors involved in choosing a good restaurant such as food, ambiance, cost, location, reviews, etc but the most important ones are cuisine, cost, and reviews. The first thing that comes to mind while choosing a good restaurant is if the cuisine you like is available at the restaurant and then the taste should also be good. The second thing is value for money, it is important that you get what you paid for. To help in the above decisions reviews come into place. They give you an idea of what the restaurant is like from people who had been to the place several times.

The dataset here has the features- Name, Cost, Total Cuisines, and Average Ratings to help in the decision making. Best restaurants in the city would be having low cost and high ratings and the number of total cuisines served.

![download (1)](https://user-images.githubusercontent.com/100950560/190747801-8dfe421d-1759-4dfc-9ce7-6f16fca79326.png)

## The Most Popular Cuisines in Hyderabad

![download (3)](https://user-images.githubusercontent.com/100950560/190749327-11befbfa-8295-40b8-b998-fc336b11ebe1.png)

Although located in South India, North Indian food is dominating in the restaurants followed by Chinese, and Continental. The number of cuisines shows the diverse food options available in Hyderabad.

## Restaurants and their Costs

![download (4)](https://user-images.githubusercontent.com/100950560/190750879-9fe429e4-05a8-4c40-994c-0ad6ea95423d.png)

The cheapest restaurants in the dataset are basically small food joints and bakeries.

Most of the restaurants fall in the range of 500-1000 INR

## Cost-Benefit Analysis

Whenever we start a business project or make a business decision we need to analyze whether the decision will be worthwhile. A Cost-Benefit Analysis is a process of analyzing the worth of a decision by estimating the costs incurred in implementing that decision and comparing them with the benefits of that decision. If the projected benefits outweigh the costs, we'll be making money out of that decision and if not, it's important to strategize a better plan.

Zomato is an Indian restaurant search and an online food delivery service. Zomato focuses on online food ordering, restaurant reservations, and loyalty programs. The target customers for the company are restaurant chains that want to reach a larger audience and application users who just want to try out local restaurants and various cuisines. Here is a simple cost-benefit analysis that can be carried out on the basis of the little information we can assume.

## Costs
When tallying costs, beginning with direct costs, which include expenses directly related to the production or development of a product or service (or the implementation of a project or business decision) which is in the case of Zomato is primarily the mobile application. Maintaining the application, strategizing plans, including the restaurants, marketing, food delivering partners and customer support needs a huge team to work on. The salaries of the employees would be a direct cost.

Other indirect costs include utilities, rent, partners, advertisers, etc.

There are some other costs that are difficult to measure such as negative reviews on the platform which leads to people avoiding the application altogether, bad presence on social media, etc.

## Benefits

The major source of Revenue is Advertising. More and more restaurants want to promote themselves on the Zomato feed in order to gain attention and visibility from a large section of Zomato subscribers and customer base.

Through the food delivery service, Zomato charges a commission to the restaurants on the basis of orders. The company earns through restaurants that pay a commission for each delivery, which is then split among the delivery partners and the company. However, online food delivery only contributes a low percentage of income compared to other revenue streams because of the huge competition and the need to provide deep discounts, etc.

## Comparison
The data that we have consists of per-person cost, cuisines available at the restaurant, and an average rating of the restaurant. If a restaurant isn't performing well in terms of rating and has a high per-person cost and a low number of popular cuisines, this is going to be a problem for Zomato. Since negative reviews would be an intangible cost to the company and with that the company will start to lose daily application users. The application users are an asset to the company, Zomato gets advertising by different restaurants because of the large audience they have.

All in all, it is important to separate out the restaurants that Zomato needs to work on in order to improve its overall customer experience and if improvement strategies don't work out, they need to delist those restaurants themselves.

## Hypotheses Generation on visualized data for Clustering

Clustering is done on the basis of similarities between the data points. The similarities are understood by how closely distanced these points are. The following are some hypotheses that can be generated by finding some similarities in the visualized data:

Restaurants with similar kinds of ratings can be clustered together. Ratings are done by people on the basis of food quality, service, packaging among other things.

Restaurants with high ratings would also probably be expensive and would be having a similar pricing strategy as well. They can be clustered according to the costs.

Restaurants having some of the most popular cuisines can be clustered together and restaurants with exotic cuisines such as Indonesian, Mexican, Japanese, etc can be clustered as they are really low in number.

## Restaurant Clustering

![download (5)](https://user-images.githubusercontent.com/100950560/190756181-ec4ca750-f1cb-404a-a68e-c302df02c99c.png)

The optimal number of clusters here would be 5. It can be clearly observed that after 5 there is minimal drop in WCSS. Let's go ahead and model for 5 clusters.
![download (6)](https://user-images.githubusercontent.com/100950560/190758109-ce988d06-d1c7-45ac-9aaf-c8e75252a053.png)


The clusters are pretty distinguishable from each other. Since the input variables were just two, it is easier to distinguish and interpret them.

Label 0 are those restaurants that were in the names dataset but weren't reviewed.

Label 1 are the restaurants that have good ratings with low pricing.

Label 2 are fine dining restaurants with good ratings and average pricing.

Label 3 restaurants are small food joints with low pricing but had average ratings.

Label 4 are expensive restaurants that also had above-average ratings.

## Sentiment Analysis

![download (7)](https://user-images.githubusercontent.com/100950560/190764687-4b686e7c-74a0-47e9-bda5-f4b5025df786.png)

For sentiment analysis used logistic regression

In the business problem, predicting the negative sentiments correctly is really important but is more important for the models to reduce the number of false positives. False positives indicate that the reviews were actually negative but they were categorized as positive and this will lead to missing a complaint to work on.

Even though the number of false negatives is higher in the case of Logistic Regression than Random Forest, it is performing better in terms of reducing False positives. This indicates that Logistic Regression is penalizing False positives more just as we want.


## Conclusion

## This is where the project ends and some of the important understandings to be drawn are:
The best restaurants in Hyderabad are AB's - Absolute Barbecues, B-Dubs, and 3B's - Buddies, Bar & Barbecue.

The most popular cuisines are the cuisines which most of the restaurants are willing to provide. The most popular cuisines in Hyderabad are North Indian, Chinese, Continental, and Hyderabadi.

The restaurants in Hyderabadi have a flexible per person cost of 150 INR to 2800 INR. The cheapest is the food joint called Mohammedia Shawarma and the costliest restaurant is Collage - Hyatt Hyderabad Gachibowli.

Upon conducting basic cost-benefit analysis on Zomato with a few assumptions one basis of the little business understanding that could be gathered, it can be concluded that it is important to separate out the restaurants with the lowest rating in order to improve its overall customer experience. These restaurants were small food joints or restaurants with high prices according to the food they are serving. Efforts should be made to advertise more and analyze the reviews, especially for these restaurants, and work on them. Mohammedia Shawarma seems to be profitable.

Restaurant Clustering was done in two approaches. First with just two features and then with all of them. Kmeans Clustering worked well in the first approach but as we increase the dimensions, it isn't able to distinguish the clusters hence principal component analysis was done and then clustered into 6 clusters. The similarities in the data points within the clusters were pretty great.

Cluster 0 - The restaurants in cluster 0 have mostly continental and fast foods available with them. The average rating is 3.42 and the average cost is 942 INR which includes an outlier of cost 2500 INR and a median cost of 600 INR. This means the restaurants are basically cheap in nature in this cluster beside one.

Cluster 1 - The restaurants in cluster 1 have mostly North Indian and other complementary foods available with them. The average rating is 3.63 and the average cost is 823 INR. These restaurants are slightly higher in prices than cluster 0.

Cluster 2 - The restaurants in cluster 2 have all the popular cuisines available with them including North Indian, Chinese and Complimentary. The average rating is 3.77 which is better than the other two clusters and the average cost is 1331 INR. These restaurants are fine dining restaurants.

Cluster 3 - The restaurants in cluster 3 have all exotic cuisines available with them including Chinese, Thai, Asian, Seafood among others. The average rating is 3.18 probably because these cuisines aren't that popular with the majority of the people in Hyderabad and the average cost is 890 INR.

*Cluster 4 *- The restaurants in cluster 4 are basically small food joints, bakeries, and cafes. The average rating is 3.14 and the average cost is 406 INR.

*Cluster 5 *- The restaurants in cluster 5 have popular cuisines available with them including North Indian, Chinese, and especially Hyderabadi. The average rating is 3.24 the average cost is 674 INR. These restaurants are casual dining restaurants with lower per-person costs and ratings than cluster 2.

Critics in the Industry were identified by grouping the customers with a good number of followers who have given more reviews with constantly low ratings. Sumit, D.S, and Ram Raju are the top three critics.

Sentiment Analysis was done on the reviews and a model was trained in order to identify negative and positive sentiments. Even though the number of false negatives is higher in the case of Logistic Regression than Random Forest, it is performing better in terms of reducing False positives. This indicates that Logistic Regression is penalizing False positives more just as we want.

## Recommendations

Restaurants with negative reviews should be worked with in order to arrive at a win-win situation.

Ratings should be collected on a category basis such as rating for packaging, delivery, taste, quality, quantity, service, etc. This would help in targetting specific fields that are lagging
