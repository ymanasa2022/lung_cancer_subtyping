# lung_cancer_subtyping
a mathematical model that can discriminate between two lung cancer subtypes
to build the model we use an unsupervised k-means clustering algorithm (Euclidean distance) of 58 NSCLC tumors using k=2.

# team_members
Manasa Yadavalli, Ziqing Zhu, Katie Alltop, Lovelyn Epelle, Shiyang Li

# key_steps
1. Load the data using the GEOparse module
2. Perform clustering using sklearn.cluster 
3. Create a DataFrame with three columns:
   a. 58 sample labels
   b. the cluster number
   c. subtype given in the dataset
4. Compute and display the accuracy of this clustering
5. Fit the model on half of the data
  a. assign a label to the clusters (AD or SCC)
  b. use the model to predict the cluster/label for the other half of the data.
6. Compute and display the accuracy of the model for the prediction results (testing data).
   Accuracy = (TP+TN)/(TP+TN+FP+FN)
7. Plot (bar plot) the 3 accuracy values for the model:
  a. train on all data 
  b. train on half of data 
     - compute the model accuracy built at point (b) on the other half of the data (test data)
8. Decide on a new feature using this data
9. Implement the feature

# deadline: Dec 7, 2023

# instructions
insert instructions on how to run the code once it's done
