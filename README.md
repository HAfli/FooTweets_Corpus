# FooTweets_Corpus
A bilingual parallel corpus of World Cup tweets

# FooTweets

******** A parallel corpus of English--German tweets *********


Project Homepage: https://github.com/HAfli/FooTweets_Corpus



GENERAL INFO:

FooTweets is a first bilingual parallel corpus for English--German tweets. A total of 4,000 English tweets are collected from the FIFA World Cup 2014 and translated into German. The English tweets are essentially informal in nature but they are translated into formal texts in German in order to help build machine translation systems that is capable of translating informal texts into the formal ones. In addition to this, each tweet is assigned with a sentiment score of either 0.3, 0.5 or 0.7 to represent the negative, neutral and positive sentiment classes, respectively.


DOWNLOAD LINK:

You need to download the files from the following link:

https://github.com/HAfli/FooTweets_Corpus


DATA FORMAT:

The corpus consists of two separate files as follows:

  (1) twitter.sent.en (English tweets), and
  (2) twitter.sent.de (German tweets)

Each of the above file contains one tweet per line and the format is as follows:

<tweet><space>|||<space><sentiment score>

Following is an example of English tweet, 
    heart Attack # WorldCup ||| 0.3


    
PURPOSE OF USE:

This corpus is mainly designed to be used for building machine translation systems for tweets. In addition to this, it can also be applied for sentiment analysis/classification tasks.




