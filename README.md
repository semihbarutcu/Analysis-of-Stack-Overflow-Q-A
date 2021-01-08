# Tidy Text Mining for StackOverflow

I used a kaggle dataset about the topic StackSample: 10% of Stack Overflow Q&A. The link for the dataset: https://www.kaggle.com/stackoverflow/stacksample

I used the Text Mining with R: A Tidy Approach by Julia Silge and David Robinson book as a reference. The link for the book: https://www.tidytextmining.com/ 

My first goal was exploring the relationship between questions and tags. A question observation consisted of an ID, OwnerUserID, CreationDate, Closed Date, Score, Title and Body. I split the words on the body part which is called as tokenizing. I did data exploration over these datasets and study sentiment analysis and tf-id. 

It's hard to work on a machine learning algorithm because of convenience of the data. Topic modeling with Latent Dirichlet Allocation (LDA) seems to be applicable on this dataset and it is a further idea to follow for me. It treats each document as a mixture of topics, and each topic as a mixture of words. 
