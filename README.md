# Airline-Customer-Satisfaction
<h2> Airline Customer Satisfaction Using Machine Learning Techniques </h2>

The airline industry is highly competitive, and customer satisfaction is crucial for building brand loyalty and retaining customers <br>

Basic exploratory data analysis (EDA) is conducted along with the analyses of the variables and their correlation. Furthermore, the Multi-Dimensionality Scaling (MDS) technique is used to pick the most relevant variables to the target variable which is customer satisfaction <br> 

Multidimensional scaling (MDS) is a technique used to visualize the similarity or dissimilarity between objects in a high-dimensional space by projecting them into a lower-dimensional space. The cmdscale() function in R performs classical MDS and takes a dissimilarity matrix as input. This dissimilarity matrix can be computed using various distance measures. In our example, we use the Gower’s coefficient. Once the dissimilarity matrix is computed, the cmdscale() function returns the coordinates of the objects in the lower-dimensional space. <br>

The goodness of fit of a multidimensional scaling (MDS) solution can be assessed using a stress plot. The aim of MDS is to find a lower-dimensional representation of the data that closely maintains the pairwise distances (or dissimilarities) between the objects. 

<h3> Machine Learning Algorithms like Logistic regression, Knn Algorithm, Decision Tree, and Random Forest algorithms were used </h3>

To achieve customer satisfaction and service quality, we have employed modelling techniques and prediction aspects from different models such as k-NN, Decision Trees, Random Forest, and Logistic Regression. We will evaluate the performance of all these models and try to fit one best-fit model that will help achieve maximum customer satisfaction. <br>

Based on our data and algorithms used, we found that the random forest algorithm was the best-suited algorithm for the dataset to predict customer satisfaction levels.

We have also employed the  LASSO regression  technique for variable selection and regularization to enhance the prediction accuracy and interpretability of the resulting statistical model. 







