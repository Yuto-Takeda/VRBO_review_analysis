# overview
Here, I analyzed the data of vacation rental properties on VRBO to determine what factors may be contributing to low ratings for certain properties.

## Sentiment Analysis
Firstly, I used Twitter-roBERTa-base transformers to label the positivity of comments. It was found that properties with good reviews had over 80% of their reviews labeled as positive, while properties with poor reviews had over 50% of their reviews labeled as negative.

## LDA model
Furthermore, I built an LDA model using the reviews labeled as negative from the low-rated properties to determine the topics that these reviews are comprised of
