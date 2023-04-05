# Overview
Here, I analyzed the data of vacation rental properties on VRBO to determine what factors may be contributing to low ratings for certain properties.

## Sentiment Analysis
Firstly, I used Twitter-roBERTa-base transformers to label the positivity of comments. It was found that properties with good reviews had over 80% of their reviews labeled as positive, while properties with poor reviews had over 50% of their reviews labeled as negative.


<img src="https://user-images.githubusercontent.com/79394001/230203398-2f726c8c-c0dc-476f-a6ff-4ecf7b0a49a5.png" width="500">


## LDA model
Furthermore, I built an LDA model using the reviews labeled as negative from the low-rated properties to determine the topics that these reviews are comprised of

![upload4](https://user-images.githubusercontent.com/79394001/230203463-6d1fd2d5-cfe0-4fc6-9273-70d628650937.png)

| Topic Num | Words |
| --- | --- |
| 1 | [room,property,us,back,get,hotel,check,dirty,outside,pictures] |
| 2 | [vrbo,stay,check,morning,place,us,owner,property,room,like] |
| 3 | List all new or modified files |
| 4 | Show file differences that haven't been staged |
| 5 | List all new or modified files |
| 6 | Show file differences that haven't been staged |
| 7 | List all new or modified files |
| 8 | Show file differences that haven't been staged |
| 9 | List all new or modified files |
| 10 | Show file differences that haven't been staged |
