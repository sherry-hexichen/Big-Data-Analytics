# Big-Data-Analytics

**Topic: US Census**
Using neural networks and a dataset extracted from the US Census, our group were tasked to develop a model to predict the income level of any individual given their demographic characteristics. To develop the **neural network**, we performed multiple iterations of neural networks with varying numbers of nodes and hidden layers, and selected the best performing model, which consisted of 2 hidden layers, each containing 64 nodes and an overall predicted **accuracy rate of 85.96%**.

**Topic: eBay Auction**
Our group were tasked to develop a model using the dataset to predict whether a new auction will be competitive. Prior to developing the model, data preprocessing was performed to ensure the data provided was adequately prepared for manipulation. 

We picked the **decision tree** model to predict the competitiveness of an auction. To begin, we created a classification tree using all predictors, and established a minimum threshold for the number of samples to be at every leaf node, enabling us to mitigate the potential risk of overfitting. Further to this, a second classification tree was created by omitting a variable that we deemed exhibited a case of reverse causality in relation to the response variable. The decision rules derived from the tree model tested a surprisingly good accuracy of 73.76%.

**Topic: Universal Bank**
Universal Bank's growth and sucess can fundamentally be attributed to client acquisition. A marketing campaign was implemented last year and the bank was able to achieve a conversion rate of 9%. Our group were tasked to develop a model that best predicts the accuracy of correctly identifying customers likely to accept a personal loan offer. After the preliminary data preprocessing steps, we proceeded with the **k-nearest neighbors algorithm**. The model was evaluated by using the k-fold cross-validation method, and achieved an **accuracy rate of 92.08%**.

