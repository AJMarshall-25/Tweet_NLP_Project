# Tweet_NLP_Project
![logo](/image/logo.png)

## Business Understanding
In the rapidly emerging tech industry, launching a new product has become increasingly difficult. New products are emerging every day, and with new launches each day, it becomes easier to have your product become lost in the shuffle. A well-crafted specialized marketing strategy is critical to the successful launch of your tech product, to ensure it receives the proper exposure. If your product isn’t falling in front of the right people, your launch is at risk of being undermined.

One of the most important outcomes of a successful product launch is customer satisfaction. When the product is well received, customer loyalty is built, and positive word-of-mouth naturally creates an elongation of your marketing efforts. It is essential to understand your customer, and how they feel, to provide optimal value to their lives with your product. Understanding customer response to your product allows for continuous improvement in the product lifespan and any additional launches going forward. As machine learning enthusiasts, we understand how to use advanced computational modeling techniques to capture customer response through their words. 

Therefore the purpose of this project is to use natural language processing to perform sentiment analysis using customer social media posts.

## Data
The data is from [data.world](https://data.world/crowdflower/brands-and-product-emotions) and is a collection of tweets surrounding the SXSW (south by southwest festival). The sentiment of approximately 9000 tweets were categorized by human raters as positive, negative, or neither, or unsure. 

![bar](/image/sentiment)

Based on our stakholder's ultimate needs to understand positive senitment of tweets, we grouped all non-positive tweets to together to form a non-positive tweets category. Thereby making a binary classification process in the modeling phase. 

### input image of new spread

## Text Processing
The nature of the text was tweets. These tweets conain mentions (@userhandle), links, hashtags, and the message itself. Tweets call for a variation in syntax based on character limitations.

## Modeling
A supervised modeling process was used. Used an iterative process 
Vectorizers were different
Initial tests were on type of models (list model types)
Results of processes BESPOKE evaluation function

## Final Model
After tuning the final model the best parameters are C=0.5, max_iter=700, solver='saga'. To evaluate this model we will pass through the validation set to prove the model performs as well on unseen data. 

## Conclusion
