---
layout: post
title: 'Bad Advice Bot: Getting kicked off of twitter'
---

Combining two of the most toxic/befuddling/incomprehensible/inscrutable parts of the internet.

[![bad advice bot](/assets/bot.jpg)](https://twitter.com/bad_advice_bot)


## Yahoo Answers: Crowdsourced bad advice
For those unfamiliar, Yahoo Answers is a crowdsourced question and answer service that launched in 2006.
It is/was notorious for having poor quality content, bad spelling and grammar, and absurd questions.
As a result, it became known as a source of [viral memes](https://knowyourmeme.com/memes/how-is-babby-formed)
and 


## Bad Advice on Twitter: A bot is born
I had always been aware of Yahoo Answers, but it wasn't until early 2014 that I learned it had a public API.
As part tech demo and part social experiment, I created [@bad_advice_bot](https://twitter.com/bad_advice_bot),
a Twitter bot that responded to questions on Twitter with somewhat relevant Yahoo Answers.

At the time, I had two goals: to experiment with the twitter API, and to make something funny.

TODO: add relevant implementation details
- searched for tweets related to relationship advice (boys/girls)
- included blacklist words
- would literally just pick out a sentence from the tweet ending in a question mark, then query yahoo answers for that question. 
    It would then just tweet as much of the first response would fit in a tweet


## Results

* Mostly just funny non-sequiturs
* A few answers were accidentally semantically correct, but still did not constitute good advice (working as intended)

I've included a few of the better interactions below:

→ TKTK link to the tweets

@bad_advice_bot ran for about 11 hours, and tweeted 66 times, roughly once every 10 minutes. Its life was tragically cut short when
the account was temporarily suspended from twitter. I took this as a sign that Bad Advice Bot should take a break from tweeting.

It looks like the Yahoo Answers API was [turned down](https://yahoodevelopers.tumblr.com/post/86260183503/yahoo-answers-apis-will-be-removed-as-of-june-3)
in June 2014. 

## Reflections

- make it personal? talk about what twitter is today? politics?
- Talk about how I would do it differently today?


- This was one of my first side-projects. It was 


# Further Reading
* [Know Your Meme: Yahoo Answers](https://knowyourmeme.com/memes/sites/yahoo-answers)
* [Techcrunch: Yahoo! Answers Launches API](https://techcrunch.com/2006/08/15/yahoo-answers-launches-api/)

