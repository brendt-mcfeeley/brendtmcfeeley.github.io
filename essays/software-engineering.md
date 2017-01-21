---
layout: essay
type: essay
title: What Got Me Involved in Software Engineering
date: 2017-01-20
labels:
  - Software Engineering
  - Computer Science
---

<img class="ui medium left floated image" src="../images/bart_soft.png">

Every since I was a little kid I was always fascinated with computers. My parents actually told me they were worried about me because I would always spend so much time using it, admittedly to only play video games. It wasnʻt until my freshman year of high school when I seriously thought about what I wanted to do in my life. Around this time I started to play around with computer hardware. I also learned to code very simple things in HTML. My brother attended a high profile college majoring in computer science and he would always tell me about the things they did in his classes. Making programs and seeing your work be created right in front of you appealed to me a lot and in my senior year of high school I decided that I wanted to major in Computer Science.

My very first computer science course was ICS 111 which was pretty much a fast paced crash course using Java. I was afraid because I felt so young and inadequete. I barely knew anything about coding and people in the class who have obviously had experience coding before were shouting out answers left and right. Our final project was to make a music video using a speciality EZ animation class to make pictures move, rotate, and scale themselves to music. I remember the feeling of watching the final product, albeit very mediocre, and thinking of how amazing it was that we (our group) was able to code this entire thing. It felt like the project took hours upon hours but the end result was worth it. I still look back at the video because itʻs hilarious but also because it is something that I took pride in back then and it made me want to dive deeper into the field of computer science.

Since my freshman year of college I have taken many more classes such as a dedicated C/C++ programming course, a database management course using SQL, and even an algorithms class. Although sometimes I struggled with some of the content of the courses, each and every class introduced to me to a wide range of topics. None of the ICS classes that I have taken so far 

## What’s a smart question?

Stack Overflow, a question and answer site for programmers, is a great resource for anyone who may have issues with code or who may simply want to learn new or different methods of doing something. There I found examples of good questions and bad questions, which could probably be improved.

In the following example, we examine the components of a decent question. In this case, the asker is trying to figure out a way to get the date of the previous month in Python.

```
Q: python date of the previous month

I am trying to get the date of the previous month with python. Here is what i've tried:

str( time.strftime('%Y') ) + str( int(time.strftime('%m'))-1 )

However, this way is bad for 2 reasons: First it returns 20122 for the February of 2012 (instead of 201202) 
and secondly it will return 0 instead of 12 on January.

I have solved this trouble in bash with:

echo $(date -d"3 month ago" "+%G%m%d")

I think that if bash has a built-in way for this purpose, then python, much more equipped, should provide something 
better than forcing writing one's own script to achieve this goal. Of course i could do something like:

if int(time.strftime('%m')) == 1:
    return '12'
else:
    if int(time.strftime('%m')) < 10:
        return '0'+str(time.strftime('%m')-1)
    else:
        return str(time.strftime('%m') -1)
        
I have not tested this code and i don't want to use it anyway (unless I can't find any other way:/)

Thanks for your help!
```

While the heading of his question could be better, it does convey what he’s trying to figure out. Usually something as brief as “python date of previous month” is what other users would enter in as search terms on Google, making it easily found. Another good thing about the question is that it’s not just a question. The asker shows what he or she has done and that he or she has put in some effort to answer the question. And while it may not be as important as the question itself, the asker shows courtesy, which does increase the chance of getting an answer.

```
A: datetime and the datetime.timedelta classes are your friend.

1. find today
2. use that to find the first day of this month.
3. use timedelta to backup a single day, to the last day of the previous month.
4. print the YYYYMM string you're looking for.

Like this:

 >>> import datetime
 >>> today = datetime.date.today()
 >>> first = datetime.date(day=1, month=today.month, year=today.year)
 >>> lastMonth = first - datetime.timedelta(days=1)
 >>> print lastMonth.strftime("%Y%m")
 201202
 >>>

```
 
The asker received six possible answers, and he or she was successful in inciting discussion from multiple users. The answers themselves were clear and were devoid of the rumored sarcasm and hostility of “hackers.” Since I myself have referenced this page and found it useful, I can confidently say that it is a good question.

## The foolproof way to get ignored.

While there are decent questions that benefit everyone, there are those one can ask to create an entirely different effect. In the following example, a user asks how he would, in short, create a desktop application with Facebook.

```
Q: Facebook Desktop Notifier

I am a beginner programmer that have never used anything other than what's included in a language.

I am trying to create a desktop application that notifies me anytime I get an update onfacebook. 
How should go about doing this? Thanks in advance.

edit Sorry I was not clear. Is there any way to make a DESKTOP application with facebook?
```

A simple “yes” would have answered the question, but we know that’s not the sort of answer he or she is looking for. Fortunately, someone kindly responded with a link to Facebook’s developer website. The asker should have done more research on his or her potential project. Then further down the road, he or she could have asked more specific and detailed questions that wouldn’t require a thousand-paged response for a sufficient answer.

## Conclusion

When we rely on others’ generosity and expertise to provide answers to our questions, it should hold that the question we ask should be one that leads to efficient and effective help that not only benefits us, but also the people we ask and others who might ask the same question in the future. Thus, if you have a question… make it a smart one! Asking questions may not always get you the best answer, but asking them in a way that will make others want to answer them will increase the success of finding a good solution and make it a positive experience on all sides.