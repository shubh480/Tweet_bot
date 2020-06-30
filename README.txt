This file provides you a walk-through on how to setup a simple twitter-bot that can do just about anything. I recently set up a simple twitter-bot that generates random cellular automata at a regular intervals. 

Twitter is a popular social network that people use to communicate with each other. Python has several packages that you can use to interact with Twitter. These packages can be useful for creating Twitter bots or for downloading lots of data for offline analysis. One of the more popular Python Twitter packages is called Tweepy. You will learn how to use Tweepy with Twitter in this app.

Tweepy

Tweepy is an easy-to-use Python library for accessing the Twitter API. There are several popular Python packages like Tweepy that serve as Twitter API wrappers, but I was only able to get my Twitterbot up and running with Tweepy.

While you test out your twitter-bot, you might want to use a throw-away Twitter account. To do this, you can make a new account associated with a new email address, or you can create an account that is linked to the same email address as your main Twitter account.

Next you login to Twitter by creating a OAuthHandler() object and setting the access token with the aptly named set_access_token() function. Then you can create an API() instance that will allow you to access Twitter.

This code will list the latest 10 post for your account. All you need to do is call me() to get the list. If you need to get more than just the latest 10, you can use the numTweets parameter to specify how many results you want.

Wrapping Up

There is much more that you can do with Tweepy. For example, you can get likes, send and read direct messages and upload media, among other things. It's a quite nice and easy to use package. You can also use Tweepy to read and write to Twitter in real-time, which allows you to create a Twitter bots. If you haven't given Tweepy a try yet, you should definitely give it a go. It's a lot of fun!