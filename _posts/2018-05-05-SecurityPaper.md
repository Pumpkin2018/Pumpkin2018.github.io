---
layout:     post
title:      An Interesting Paper Related to Android Application Security
subtitle:   Feat. Weekly Summary 1.
date:       May 4, 2018
author:     Qin
header-img: img/post-bg-coffee.jpeg
catalog: true
tags:
    - Summary
---

This paper is named "Stack Overflow Considered Harmful? The Impact of Copy&Paste on Android Application Security", which is published on the top conference IEEE Symposium on Security and Privacy 2017. Actually, this paper is from the paper set related to the smart phone security and privacy issues collected by Cody. Thanks to him!

As the title shows, this paper is focusing on the problem of application security considering that more and more programmers seek for help on the online community, e.g., Stack Overflow, by easily copying and pasting the code snippets into their own projects. The authors have the concern that the original code snippets may have vulnerabilities, resulting in severe security problems in the user-end applications.

They took a five-step scheme to accomplish this work.
1. Discussion threads from Stack Overflow are crawled.
2. JavaBaker is employed to exact those security-related code snippets.
3. SVM is utilized to classify the secure code snippets and the insecure ones, which is similar to document classification problem.
4. WALA is employed to generate abstract representation of each insecure code snippet.
5. Program Dependency Graphs (PDG) is used to detect the similar code snippets in Apps.

Even though I have no background knowledge about the detailed techniques, this paper impressed me a lot. Since the real-life problem they found is of great importance.



Besides, I'd like to have a brief summary of what I did and obtained in this week.

* Help Dr. Wang review two masters' dissertations from last Sunday to this Monday. One is related to the cognitive radio network, and the other is crowdsourcing based on Stackelberg game and mechanism design.
* Help Donghui revise his paper.
* Read more papers about the topic I'm interested in and form the basic idea.
* Establish my own blog.