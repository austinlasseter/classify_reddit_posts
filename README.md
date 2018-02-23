# ENGAGE!
## A predictive tool for maximizing reader engagement on Reddit

### What fires readers up?
Reader engagement on Reddit:
* Gets the message out
* Persuades public opinion
* Can lead to profit

### OUR TOOL CAN PREDICT READER ENGAGEMENT FOR YOUR POST
DATA SOURCE
* Hosted scraper on AWS EC2
* 1,000 posts every 6 hours
* Ran for 5 days
* Collected 37,000 posts
* Reduced to 5,300 unique

### DATA COMPONENTS
* Title of Post
* Subreddit
* Length of Time
* Number of Comments

### WHAT TO LOOK FOR?
* 73 Comments: That’s all it takes to hit the top half of reader-engaged posts.
* What’s the average length of popular Reddit posts? About 50 characters
* It takes some time to achieve reader engagement: About 9 hours
* 25% of subreddits account for almost 95% of all comments!

### Secret Sauce
We call “vectorization” the process of turning text into numbers so that we can predict an outcome
Using this tool, we can predict what text is likely to engage readers more!

### Modeling
Using these features, we tried
PREDICTING ENGAGEMENT 3 DIFFERENT WAYS 
* K Nearest Neighbors
* Logistic Regression
* Random Forest

## 538 SHOULD INVEST IN OUR PREDICTIVE TOOL
Our tool outperforms competitors:
* Accuracy (61.4%)
* ROC/AUC Score (61.4%)
For each post, the tool produces a probability score based on:
* length, subreddit, timing
* content of your post
Can be enhanced with funding








