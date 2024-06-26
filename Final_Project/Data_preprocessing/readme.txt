Data_preprocessing:

In the first component, we mainly focus on data cleaning and data
preparation. Given the status updates and the results of assessment
questionnaires, we build a dataset of users whose mental states are
estimated.

The myPersonality is a Facebook application that allows its users to participate in psychological research by filling in questionnaires.

IPIP is a questionnaire measures individuals on the five dimensions of personality defined by the Five-Factor Model of Personality. The test consists of questions that the user must rate on how true they are about themselves on a five-point scale, where 1 = Disagree, 3 = Neutral and 5 = Agree. The higher the score, the more agreeable the personality dimension is to the question.
As the output of this process, we extract five numerical features representing the personality traits of users.


---------------------------------------------------------------------
for us:


--> We first import the my personality dataset and print it

--> 'My_personality.csv' has #authid, status that the person has tweeted, the 5 OCEAN values, additional properties

--> Then we do all the preprocessing like stopword removal,converting to lowercase,remove rare words, translating languages, converting emoticons to text, removing urls etc

--> we assign random names to the unknown users

--> for this we upload the names dataset which contains randomly generated names

--> we do a sentiment analysis using the preprocessed dataset. This analysis is done using nltk 'SentimentAnalyzer' package