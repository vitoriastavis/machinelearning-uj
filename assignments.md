Please do not add the  .ipynb files to repository.

Please update your repo to refelct the last changes in my repository.

# Banknotes NB

31.05.23

OK!! but you  could have just used the GaussianNB from sklearn :)

# Banknotes GMDA 5/15

21.06.23

A. OK 

But if you have used normalisation='true' in the confustion_matrix(...) you do nat have to normaliza the tp, fp, etc. They are aalready normalised.

B. OK

C. 

You should find the number of cluster that gives best classifiction, that is  for each number of compenents you should consruct a full classifier as in B, calculate f1  or auc score and compare that. 

D. 

You got the numbers wrong false positive is a genuine banknote classified as counterfeit. The cost is 15. 
The pobability of genuine banknote is 0.99. 

False negative is a counterfeit banknote classified as genuine. The cost is 100, but the probability of counterfeit banknote is 0.01


# Banknotes NN 5/5

21.06.23

Very good ! But BCELoss and CrosseEtropy loss are the same in case of binary classfication. 

# Titanic

31.05.23

## Problem b

Your TPR and FPR calculations are wrong. What you have in the second if clause should be false negative. 

21.06.23

Your TPR and FPR calculations are still wrong. Please calculate correctly the number of positives and negatives. 

## Problem d 3/5

Your implementation is wrong. You are implementing an gaussian Naive bayes classifier but should be categorical. Just use the CategoricalNB from sklearn. 

21.06.23

OK :) 


