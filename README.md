# Amazon_Vine_Analysis
## Overview
In this module we used a combination of PySpark and an AWS database with Postgres to analyze reviews for kitchen gadgets.
## Results
There is a portion of paid reviews called Vines in Amazon Reviews. We were able to deterime that paid reviews don't always result in higher number of 5 star reviews. 
- The first model used a Random Over Sampler with Logistic Regression. The accuracy of this model was about 60.2%. 
![](https://github.com/ryanstaudhammer/Credit_Risk_Analysis/blob/main/Resources/ROS.png)
- Next was SMOTE Oversampling. The accuracy of this model was about 62.8%. 
![](https://github.com/ryanstaudhammer/Credit_Risk_Analysis/blob/main/Resources/SMOTE.png)
- Next was Cluster Centroids. The accuracy of this model was about 52.0%. 
![](https://github.com/ryanstaudhammer/Credit_Risk_Analysis/blob/main/Resources/CC.png)
- Next was SMOTEENN. The accuracy of this model was about 63.8%. 
![](https://github.com/ryanstaudhammer/Credit_Risk_Analysis/blob/main/Resources/SMOTEENN.png)
- Next was Balanced Random Forest Classifier. The accuracy of this model was about 76.0%. 
![](https://github.com/ryanstaudhammer/Credit_Risk_Analysis/blob/main/Resources/RFC.png)
- Finally was Easy Ensemble Classifier. The accuracy of this model was about 93.3%. 
![](https://github.com/ryanstaudhammer/Credit_Risk_Analysis/blob/main/Resources/EEC.png)
## Summary
The number of paid 5 star reviews was not higher than just regular reviews.
