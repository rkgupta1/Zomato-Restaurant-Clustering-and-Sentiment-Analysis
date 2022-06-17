<p align="center"> 
  <img src="image\food.png" alt="Food Logo.png" width="280px" height="140px">
</p>
<h1 align="center"> Zomato Restaurant Clustering and Sentiment Analysis </h1>
<h3 align="center"> AlmaBetter Verified Project - <a href="https://www.almabetter.com/"> AlmaBetter School </a> </h5>

<p align="center"> 
</p>
<h2> Problem Statement and Project Description</h2>

<p>Zomato is an Indian restaurant aggregator and food delivery start-up founded by Deepinder Goyal and Pankaj Chaddah in 2008. Zomato provides information, menus and user-reviews of restaurants, and also has food delivery options from partner restaurants in select cities.
The Project focuses on Customers and Company, you have to analyze the sentiments of the reviews given by the customer in the data and make some useful conclusions in the form of Visualizations. Also, cluster the zomato restaurants into different segments. The data is visualized as it becomes easy to analyze data at instant. The Analysis also solves some of the business cases that can directly help the customers finding the Best restaurant in their locality and for the company to grow up and work on the fields they are currently lagging in.
This could help in clustering the restaurants into segments. Also the data has valuable information around cuisine and costing which can be used in cost vs. benefit analysis
Data could be used for sentiment analysis. Also the metadata of reviewers can be used for identifying the critics in the industry.</p>

<p>India is well-known for its unique multi-food cuisine, which is offered in a huge number of restaurants and hotel resorts and symbolizes unity in variety. In India, the restaurant industry is changing rapidly. More People are appealing to the concept of eating restaurant meals, whether they dine outside or have food delivered to their homes. The increasing number of restaurants in every Indian state has encouraged an analysis of the information to gain some insights, noteworthy facts, and statistics about the Indian food sector. 

As a result, the purpose of this study is to analyze Zomato restaurant data in Hyderabad. Zomato is a restaurant aggregator and food delivery service based in India. With the use of unsupervised and supervised machine learning algorithms, the work here clusters restaurants into distinct segments and evaluates the sentiments in customer reviews. The analysis also resolves several business cases that can directly assist customers in locating the best restaurant in their area, as well as the company's growth and development in areas where it is currently underperforming.<p>

<h2> :floppy_disk: Project Files Description</h2>

<p>This project contains an executable file, a technical document and a presentation as follows:</p>
<h4>Executable Files:</h4>
<ul>
  <li><b>Zomato_Restaurant_Clustering_and_Sentiment_Analysis_Vithika_Karan.ipynb</b> - Google Collab notebook containing data summary, exploration, visualisations, clustering and sentiment analysis.</li>
</ul>

<h4>Documentation:</h4>
<ul>
  <li><b>Technical Documentation.pdf</b> - Includes the complete documentation about the project.</li>
  <li><b>Project Presentation- Clustering.pdf</b> - Presentation of the same.</li>
</ul>


![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

<h2> :book: K Means Clustering</h2>

<p>K-means clustering is a widely used unsupervised machine learning technique.Unsupervised algorithms make inferences from datasets using only input vectors and do not relate to known or tagged outcomes.
A cluster is a collection of data points that have been grouped together due to particular commonalities.
K, for the number of centroids required in the dataset. The centroid is an imaginary or real point that represents the cluster's center.By lowering the in-cluster sum of squares, each data point is assigned to one of the clusters.

To put it another way, the K-means algorithm finds k centroids and then assigns each data point to the closest cluster while keeping the centroids as small as possible.
The 'means' in K-means refers to the data being averaged, or determining the centroid. K means is highly vulnerable to high dimensional data. As the dimensions increase it is not able to differentiate between the clusters. Hence, a dimensionality reduction technique called Principal Component Analysis was used,

<img src="image/kmeans.png" alt="Kmeans Clustering" style="max-width:60%;"></p>

<h2> :book: Principal Component Analysis </h2>
<p>Principal Component Analysis, or PCA, is a dimensionality-reduction approach for reducing the dimensionality of large data sets by transforming a large collection of variables into a smaller one that retains the majority of the information in the large set.

Naturally, reducing the number of variables in a data collection reduces accuracy; nevertheless, the answer to dimensionality reduction is to trade a little accuracy for simplicity. Because smaller data sets are easier to study and visualize, and because machine learning algorithms can analyze data more easily and quickly with fewer variables to process. It takes and builds orthogonal principal components to explain the variance between the data in a descending order. It means, the first component will have the highest variance and then the next and so on.

<img src="image/pca.png" alt="Principal Component Analysis" style="max-width:60%;"></p>


![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

<h2> :chart_with_upwards_trend: Exploratory Data Analysis</h2>
<p>The best restaurants in Hyderabad are AB's - Absolute Barbecues, B-Dubs, and 3B's - Buddies, Bar & Barbecue.
The most popular cuisines are the cuisines which most of the restaurants are willing to provide. The most popular cuisines in Hyderabad are North Indian, Chinese, Continental, and Hyderabadi.</p>
<img src="image/best.png" alt="Best restaurants" style="max-width:70%;"> 

<img src="image/cuisines.png" alt="Cuisines" style="max-width:70%;">

<p>Upon conducting basic cost-benefit analysis on Zomato with a few assumptions one basis of the little business understanding that could be gathered, it can be concluded that it is important to separate out the restaurants with the lowest rating in order to improve its overall customer experience. These were the restaurants with lowest rating and high price sorted in that order. Efforts should be made to advertise more and analyze the reviews, especially for these restaurants, and work on them. Mohammedia Shawarma seems to be profitable.</p>

<img src="image/worst.png" alt="Worst Restaurants" style="max-width:70%;">

<p>Critics in the Industry were identified by grouping the customers with a good number of followers who have given more reviews with constantly low ratings. Sumit, D.S, and Ram Raju are the top three critics.<p>
<img src="image/critics.png" alt="Critics" style="max-width:70%;"> 

<p>Looking at the words involved in the reviews of the restaurants with low ratings it can be understood that the customers didn't like the taste, had worst experience, or maybe the order packaging wasn't good. Some of these restaurants had medium-ranged prices.</p>
<img src="image/sentiment.png" alt="Critics" style="max-width:70%;"> 




<h2> :chart_with_upwards_trend: Results</h2>
<p>Restaurant Clustering was done in two approaches. First with just two features and then with all of them. Kmeans Clustering worked well in the first approach but as we increase the dimensions, it isn't able to distinguish the clusters hence principal component analysis was done and then clustered into 6 clusters. The similarities in the data points within the clusters were pretty great.</p>
<img src="image/cluster1.png" alt="cluster" style="max-width:70%;">


<p>Cluster 0 (Purple) - The restaurants in cluster 0 have mostly continental and fast foods available with them. The average rating is 3.42 and the average cost is 942 INR which includes an outlier of cost 2500 INR and a median cost of 600 INR. This means the restaurants are basically cheap in nature in this cluster beside one.

Cluster 1 (Red) - The restaurants in cluster 1 have mostly North Indian and other complementary foods available with them. The average rating is 3.63 and the average cost is 823 INR. These restaurants are slightly higher in prices than cluster 0.

Cluster 2 (Blue) - The restaurants in cluster 2 have all the popular cuisines available with them including North Indian, Chinese and Complimentary. The average rating is 3.77 which is better than the other two clusters and the average cost is 1331 INR. These restaurants are fine dining restaurants.

Cluster 3 (Green) - The restaurants in cluster 3 have all exotic cuisines available with them including Chinese, Thai, Asian, Seafood among others. The average rating is 3.18 probably because these cuisines aren't that popular with the majority of the people in Hyderabad and the average cost is 890 INR.

Cluster 4 (Yellow) - The restaurants in cluster 4 are basically small food joints, bakeries, and cafes. The average rating is 3.14 and the average cost is 406 INR.

Cluster 5 (Black) - The restaurants in cluster 5 have popular cuisines available with them including North Indian, Chinese, and especially Hyderabadi. The average rating is 3.24 the average cost is 674 INR. These restaurants are casual dining restaurants with lower per-person costs and ratings than cluster 2.</p>
<img src="image/cluster2.png" alt="cluster" style="max-width:70%;">

<p>In the business problem, predicting the negative sentiments correctly is really important but is more important for the models to reduce the number of false positives. False positives indicate that the reviews were actually negative but they were categorized as positive and this will lead to missing a complaint to work on.</p>
<img src="image/logistic.png" alt="cluster" style="max-width:40%;">


![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

<!-- CREDITS -->
<h2 id="credits"> :scroll: Credits</h2>

< Vithika Karan > | Keen Learner | Business Analyst | Data Scientist | Machine Learning Enthusiast

<p> <i> Contact me for Data Science Project Collaborations</i></p>


[![LinkedIn Badge](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/vithika-karan/)
[![GitHub Badge](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/vithika-karan)
[![Medium Badge](https://img.shields.io/badge/Medium-1DA1F2?style=for-the-badge&logo=medium&logoColor=white)](https://medium.com/@vithika16k)
[![Resume Badge](https://img.shields.io/badge/resume-0077B5?style=for-the-badge&logo=resume&logoColor=white)](https://drive.google.com/drive/folders/1Y_MuQu-nm_EWUGiFsydd-c4EkaLeAkZi?usp=sharing)


![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)
<h2> :books: References</h2>
<ul>
  <li><p> Dr Michael J Garbade, 'K Means Clustering'. [Online].</p>
      <p>Available: https://towardsdatascience.com/understanding-k-means-clustering-in-machine-learning-6a6e67336aa1</p>
  </li>
  <li><p>Builtin.com, 'Principal Component Analysis'. [Online].</p>
      <p>Available:https://builtin.com/data-science/step-step-explanation-principal-component-analysis</p>
  </li>
  <li><p>Prashant Sharma, 'Understanding K Means'. [Online].</p>
      <p>Available: https://www.analyticsvidhya.com/blog/2021/11/understanding-k-means-clustering-in-machine-learningwith-examples/</p>
  </li>


![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

