# Covid-19 tweets

## Objective of the project: 
By using the package "tweepy" allowing the use of the Twitter API, this project brings together all the tweets evoking covid 19 since March 20, 2020 in a database. 

## Contents 
<br/>1. **covid19_tweets.ipynb**
<br/>Jupyter Notebook which allows to: 
- update the database containing tweets 
- process text variables 
- analyse the database 

<br/>2. **requirements.txt**
<br/> Versions of the python libraries used 
<br/>
<br/>You can install the dependencies with the following command-line:

```
pip install -U -r requirements.txt
```

<br/>3. **dictionnary.txt**
<br/> Data dictionary giving: 
- Name of the variables
- Types of the variables
- Descriptions of the variables 
- Modalities if they are categorical variables 

<br/> 

## Twitter API installation 
<br/>1. **In the Jupyter Notebook run the first cell:**
```
!pip install tweepy
```


<br/>2. **If this installation does not work, follow the steps below:**
- Create a Twitter account if you don’t have one: https://twitter.com/?lang=fr
- For keeping your account secure a tel number is required. You can use this help: https://help.twitter.com/en/managing-your-account/how-to-add-a-phone-number-to-your-account
- For create an app, go to this link:  https://developer.twitter.com/en/apps
- Follow the instructions (take care of specify if the API will be use for governmental entity) 
- Save your API keys and API secrets, they will be use in the second part of the Jupyter Notebook. 
- You have now access to Twitter API v2. 

<br/>3. **However, for this project, you need elevated access:**
- Go to your dashboard ⇒ Products ⇒ Select elevated
- Answer questions about the purpose of your use of the API. This link is a help to answer the  questions: https://developer.twitter.com/en/support/twitter-api/developer-account
- Wait the confirmation 



