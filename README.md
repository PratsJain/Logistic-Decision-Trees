# Logistic-Decision-Trees
We trained the Decision Tree classifier on below mwntioned three datasets by using Logistic
regression as the algorithm/function to split the node. We implemented the decision tree classifier from scratch, using the entropy method to determine the best split amongst the splits obtained from Logistic Regression. We also reported the metrics precision, recall, accuracy and
AUC-ROC curve. <br>
We imlemented 2 versions of this idea: <br>
• One attribute for the split. <br>
• Pair of attributes at each node for the split. <br>
The datasets are: <br>
Dataset1:  https://christophm.github.io/interpretable-ml-book/cervical.html <br> 
Target class column: The biopsy results ”Healthy” or ”Cancer”. <br>
Dataset2:  https://drive.google.com/drive/folders/13C3qsUMSXY_MIlO4GJrJ-yRmA55aIjaE <br>
Target class column: ”fetal_health”. <br>
Dataset3:  https://github.com/AndrzejSzymanski/TDS/blob/master/banking.csv <br>
Target column: last column <br>
We wrote custom code for printing the decision tree and analyse the rules output.
We performed 5 fold cross-validation and reported the performances (P,R,F1,accuracy). We also
looked into statistical tests (example: student-t tests) to check whether the performences of the algorithms are statistically significant or not.
We found that one-attribute split was better for dataset 1 and two-attribute split was better for datasets 2 and 3.
We provide the jupyter notebook for the same.
