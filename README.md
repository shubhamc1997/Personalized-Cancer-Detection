I.	 INTRODUCTION
Once sequenced, a cancer tumor can have thousands of genetic mutations. But the challenge is distinguishing the mutations that contribute to tumor growth (drivers) from the neutral mutations (passengers). Currently this interpretation of genetic mutations is being done manually. This is a very time-consuming task where a clinical pathologist has to manually review and classify every single genetic mutation based on evidence from text-based clinical literature. This step has to be replaced by an automated Machine Learning model.

II.      PROBLEM DEFINITION
There are nine different classes a genetic mutation can be classified into => Multi class classification problem. Classify the given genetic variations/mutations based on evidence from text-based clinical literature keeping in mind the real-world/Business objectives and constraints. 
Real-World/Business Constraints:
 1. Interpretability is important since a doctor needs to know the reason behind making a decision.
 2. Errors can be very costly so we use log-loss as a metric for measurement since it penalizes errors.
 3. Probability of a data-point belonging to each of the 9 classes is needed as if the probabilities for 2 classes are similiar(say 0.55       and 0.45), the the clinical pathologist can conduct further research.
 
III.    SCOPE/IMPORTANCE OF PROJECT
To reduce the time taken by a clinical pathologist to manually review and classify every single genetic mutation by training a Machine Learning model to automatically classify genetic variations. 

IV.     METHODOLOGY
The methodology followed for this project consists of the following:
1.Exploratory Data Analysis (Reading the data, Preprocessing of text, Train, Test and Cross-Validation Split).
2.Univariate Data Analysis on Gene and Text Feature.
3.Applying Machine Learning Models(Base Line Model – Naïve Bayes, K Nearest Neighbor Classification, Logistic Regression with and without   Class Balancing, Linear Support Vector Machines, Random Forest Classifier with one-hot encoding for hyper parameter tuning,  hyper-       parameter tuning is applied on all models and  all models are tested with best hyper-parameters.)
4.Stacking the models.
5.Performance metric – Multi class log-loss and Confusion matrix.
