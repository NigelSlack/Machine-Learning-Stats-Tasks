# GMIT HDip Data Analytics 2020
# Machine Learning and Statistics Tasks

The four tasks for the module are contained in the single jupyter notebook in this repository.
Step through the notebook sequentially to run each task in turn.  

Task 1 - Find the square root of 2 to 100 decimal places without using standard libraries.  
         The square root is calculated using integer arithmetic and Newton's method, then two checks are performed to verify the answer -  
           finding the known square root of another number, 4  
           using the library 'decimal' to get the square root  
           
Task 2 - Perform a Chi-squared statistical test against a small table obtained from the Wikipedia page about Chi-squared, and provide some analysis of the test. Confirm the statistical value is approximately 24.6, and get the associated p-value.
  An explanation of the Chi-squared test is given
  A small table from Wikepedia giving the hypothetical areas of residence of three groups of people, based on occupation type, is analysed using Chi-squared, the expected values are confirmed and the results are discussed
  
Task 3 - Assess two Excel algorithms that provide values for Standard Deviation - STDEV.P and STDEV.S
  The reason for the difference between the two algorithms is explained (known as Bessel's correction), and the standard deviations of samples from different sets of random numbers are examined both with and without the correction. The results are analysed to assess the effectiveness of the algorithms.

Task 4 - Use scikit-learn to apply k-means clustering to Fisher’s famous Iris data set. Explanation of how the code works, how accurate it might be, and how the model can be used to make predictions of species of iris.        
  Plots are made of the well known dataset to visualise the distribution of measurements, then a kmeans clustering model is trained using the dataset, and the resulting clusters are compared to the distributions of the petal and sepal lengths/widths. The results are discussed, and the accuracy of the groupings are assessed. Scaling the input values is also examined, as are the results from multiple executions of kmeans. Finally the model is used to predict which species sample test measurements are likely to belong to, having created 3 sets of test values to be deliberately clearly within the groupings for the 3 species of Iris.
           
