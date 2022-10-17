# EC601_project2

**Phase1:**

Twitter APIs
When I want to following from the twitter api, I can use following_lookup. I get this program from twitter API. I connect it with my bear token. I also connect it to my twitter id. 
In this program, requests and json lib are used. Using get and bear_auth will help me to fetch data from database.
![alt text](https://github.com/xu842251462/EC601_project2/blob/master/img.png)
![alt text](https://github.com/xu842251462/EC601_project2/blob/master/img_1.png)


Google NLP
Building Sentiment analysis model using GoogleNLP library.

Text result:
Text1 : “I am sad today because I got cough”

The text entered should be predicted as a negative emotion since keywork “sad”, “a lot of homework”

Result: the test shows a negative score of -0.8. It is a large negative socre which shows it is a negative emotion.

Text2: “I want to go to the zoo.”

The text entered should be neutral since it contains no emotional words.

Result: the test shows a score of 0.2 which shows no indication for positive or negative emotion.

Text3: “I like the beautiful sunshine.”

The text contains positive emotion word” beautiful.”

Result. Test score 0.89 which is high positive emotion.

**Phase2:**

MVP: extracting emotion trend of tweets in a given time.

User Story: Developer can use the emotion trend of tweeter to find the preference of the user. When there is ceremony, we can find the positive emotion in the twitter. When user get bad grade on exame, they may post the negative emotion in the post.


