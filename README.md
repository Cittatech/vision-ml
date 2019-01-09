# vision-ml
Skip to content
 
Search or jump to…

Pull requests
Issues
Marketplace
Explore
 @Cittatech Sign out
1
0 0 Cittatech/vision-ml
 Code  Issues 0  Pull requests 0  Projects 0  Wiki  Insights  Settings
vision-ml/Architecting-For-ML-on-Amazon-SageMaker-master/Predictor-Readme
94a5982  14 hours ago
 Ajay Sharma Changes to approach document
     
22 lines (16 sloc)  848 Bytes
Predictor Team Approach
Objective - To identify if we can predict if the ship is identified in the image
1/8/19 - Accomplishments 
The following steps were completed.
    a. Environment was setup in SageMaker with 100 GB space and we used c5Xlarge type
    b. Created Kaggal account and downloaded Kagaal API keys 
    c. Installed Kaggal account into Sagemaker notebook 
    d. Downloaded the Kaggal data/library using the Kaggal API
    e. Created S3 buckets to uploaded the data
    f. Decided the approach of using the algorithm "Image object-detection Algorithm"
    e. We have decided two-step approach.
      1. See if any block exists in the image 
      2. If there is a-block then match the pattern to determine if it a ship
      
   Tomorrow - Plan
   1. Copy all  test data to S3 bucket
   2. Build the model and test it
   
      

 
