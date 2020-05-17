---
published: true
layout: post
title: Landing on a Stable Instance of Tensorflow on Amazon to Train Models
date: 2020-05-16T12:00:00.000Z
tags:
  - Collections
  - Models
image: >-
  https://s3.amazonaws.com/kinlane-productions/algo-rotoscope/stories/markets/feed-the-people-economics.jpg
---
I have bounced around quite a bit from the original Tensorflow model I was using when I started this work. Algorithmia had done a lot of the heavy lifting for me, but that original Amazon Web Services machine image eventually fell into disrepair and I couldn't operate it anymore. For the last couple of years I bounced around trying different text transfer services, and kicking the tires on a variety of Tensorflow models that were cheaper to operate, but none of them produced the same results as some of the earlier models I had developed. To make things worse, I had accidentally deleted some of my earlier models, leaving me pretty determined to produce my own machine learning model.

Well, after much experimentation I finally created one that works as well as the first model I had. Actually, it is the same model, I just managed to find the original source of how to build it, followed their instructions and then I was able to get up and going. I will do a formal write-up on it citing my sources, and walking through how I did what I did. I just haven't had time to write it up -- each time I go to operate it and apply to my current batch of images I have to retrain myself on how it all works. Eventually I've carve out enough time to write up an on-boarding document for it, and publish it here on the blog for this work.

I'm just looking to draw a line in the sand here on the updates for when I finally got full control over how I train my models. So when I'm looking back I can better understand what images were from the first batch of models, what came the years in between, and what has been produced as part of this new process. There are distinct differences between each of the phases, how I trained each model, the length of time, and ultimately how I chose to apply them. Back in 2016 I had the money to run a GPU server for two months straight. I don't have those kind of resources today, but I'm regularly funneling money into it whenever I can. Then step back occasionally and organized what I've produced into collections that I can use to showcase what I am seeing in my head when it comes to how AI, ML, APIs, and the Internet are being used to distort not just our online worlds, but our physical worlds as well.
