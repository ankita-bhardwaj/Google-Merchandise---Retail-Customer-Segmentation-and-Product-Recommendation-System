# Google Merchandise- Retail Customer Segmentation and Product Recommendation System

# 1.Introduction
E-commerce is a $4.9T industry worldwide and has been growing exponentially over the years. Understanding customer behaviour and the potential revenue that can be generated is crucial to any e-commerce store so that they can make better strategic and operational decisions. Predicting the behaviors of the customers can be used to better target ads and provide product recommendations. In this project, we analyzed the Google Merchandise Store (also known as GStore, where Google swag is sold) customer dataset. We hope to achieve an actionable outcomes to drive better operational and marketing budgeting strategies for sellers that choose to use data analysis on google analytics platform. In addition, we aimed to provide personalized product recommendation to the users based on the customer segment in which they fall.

# 1.1	Problem Statement
The main objectives of this project are:
- Identify different customer segments in the data set so that Google can understand customer preferences with respect to the merchandise. This will help Google and third party sellers devise and implement targeted marketing campaigns for certain types of products.
- For customers within a segment, identify products that they might be interested based on what the peers in the segment have viewed and/or purchased. This will help Google provide a personalised service to the customers while also increase the time spent on the website in the hope that the customers will eventually make a purchase. 

# 2.	Methods
In order to build the model, the problem was approached in sequential steps:
- Data Cleaning
- Clustering using K-Means (Unsupervised method) algorithm
- K-nn (Supervised method) on the clusters identified to recommend products 

# 3. Results

By using the results from K-means and K-nn algorithms, we achieved the result of recommending products when we know the product that is viewed by a customer. To demonstrate this, we created a function to take the input of a product name and output its 3 nearest products. 


# 4. Limitations of the Approach:
Though this model provides recommendations for a product, there are certain limitations to the model.
- The model assumes all features to be equally significant, i.e. does not take into account the weights of different features in the K-NN Algorithm. 
- The model can perform significantly better with more features and more data.
- Limited computational capacity restricted the model and hence.


# 5. Business Application
Customer segmentation based on clusters can be used for effective marketing strategies

- Retail marketers are constantly looking for ways to improve the effectiveness of their campaigns. One way to do this is to target customers with the particular offers to deepen customer loyalty and improve revenue generated per customer. Marketer’s goal is to make the most relevant match between customer and offer. This can be achieved by targeting specific groups of people with concentrated interests. Clustering similar customers together is a practical method to improve the effectiveness of marketing. The two main advantages of cluster analysis over simple threshold/rule-based segmentation are

  a. practicality – it would be practically impossible to use predetermined rules to segment customers over many dimensions
  
  b. homogeneity – variances within each resulting group are very small in cluster analysis, whereas rule-based segmentation typically      groups customers who are actually very different from one another.


- Recommending similar products to a user viewing a product on Google platform
One of the best tools a retailer has for selling products to customers is providing product recommendations. And customers love product recommendations that are tailored based on their interests and historical behaviour. The recommendations are also a way to improve customer loyalty and hence, increase customer lifetime value (CLTV).


