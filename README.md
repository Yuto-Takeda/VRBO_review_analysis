# **Overview**
Here, I analyzed the data of vacation rental properties on VRBO to determine what factors may be contributing to low ratings for certain properties.

## **Sentiment Analysis**
Firstly, I used Twitter-roBERTa-base transformers to label the positivity of comments. It was found that properties with good reviews had over 80% of their reviews labeled as positive, while properties with poor reviews had over 50% of their reviews labeled as negative.


<img src="https://user-images.githubusercontent.com/79394001/230203398-2f726c8c-c0dc-476f-a6ff-4ecf7b0a49a5.png" width="300">

<img src="https://user-images.githubusercontent.com/79394001/230203403-3bad1297-1b7e-4d46-8380-549e1b6fc36d.png" width="300">

<img src="https://user-images.githubusercontent.com/79394001/230203407-833fa149-4a51-4210-9175-8558094e43ce.png" width="300">


## **LDA model**
Furthermore, I built an LDA model using the reviews labeled as negative from the low-rated properties to determine the topics that these reviews are comprised of

#### The word cloud of the data used in the LDA model

<img src="https://user-images.githubusercontent.com/79394001/230203463-6d1fd2d5-cfe0-4fc6-9273-70d628650937.png" width="500">

#### The result of the LDA model

| Topic Num | Words |
| --- | --- |
| 1 | [room,property,us,back,get,hotel,check,dirty,outside,pictures] |
| 2 | [vrbo,stay,check,morning,place,us,owner,property,room,like] |
| 3 | [stay,hotel,also,check,floor,dirty,room,broken,rooms,like] |
| 4 | [house,property,day,vrbo,stay,back,apartment,like,check,owner] |
| 5 | [stay,place,vrbo,room,owner,book,horrible,booked,days,hotel] |
| 6 | [room,place,get,two,never,dirty,us,time,check,stay] |
| 7 | [room,check,get,back,property,us,hotel,owner,place,vrbo] |
| 8 | [room,place,property,never,vrbo,us,hotel,called,night,people] |
| 9 | [property,stay,room,place,like,owner,get,check,even,night] |
| 10 | [room,property,get,check,us,unit,dirty,hotel,good,services] |
