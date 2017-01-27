---
layout: essay
type: essay
published : false
title: Smart Questions vs. Bad Questions and Why They Matter
date: 2017-01-26
labels:
  - Software Engineering
  - Communication
  - Learning
  - Stack Overflow
---

## What is a smart question?
Everyone has heard the saying "There is no such thing as a stupid question." Most of us probably know someone that likes to ask dumb questions or have seen something online that make us do a mental double take. 
<p align="center">
  <img src="../images/simon.png" height="250" width="325"/>
</p>
We just need a couple of extra seconds to comprehend what they asked. A smart question is a question that relays your thoughts and questions in a detailed manner, but also in a short and precise manner. In addition a smart question should show that you put in effort trying to find the answer you're looking for.

Here is an example from user duplode on [StackOverflow.](http://stackoverflow.com/)

```
Question : Why is it faster to process a sorted array than an unsorted array?
Here is a piece of C++ code that seems very peculiar. For some strange reason, sorting the data miraculously makes the code almost six times faster.

// C++ code that duplode has provided here.

Without std::sort(data, data + arraySize);, the code runs in 11.54 seconds.
With the sorted data, the code runs in 1.93 seconds.
Initially, I thought this might be just a language or compiler anomaly. So I tried it in Java with a somewhat similar but less
extreme result.

My first thought was that sorting brings the data into the cache, but then I thought how silly that is because the array was just generated.

What is going on?
Why is a sorted array faster to process than an unsorted array?
The code is summing up some independent terms, and the order should not matter.
```

This is an example of a smart question because he is very precise and to the point. He has questions about what is happening and shows that he has put some previous thought into his question by providing tests/examples in multiple languages to show that it is a universal problem.

## Now, what is not a smart question?
A bad question (or not so smart question) is a question where the person jumps straight to the conclusion and wants answers right away without trying any other solutions out first. For example, someone is having trouble with their code and it does not work, this person then decides that instead of searching around on forums or looking at websties like StackOverflow for people that had similar problems, they deicde to hop on StackOverflow themselves and immedietly ask for help. 
without explaining that they have tried alternative methods but had failure.

Here is an example from user Mitchell on [StackOverflow.](http://stackoverflow.com/)

```
Question : i am developing my first app and i cannot figure out this error here is my code
this is my code. can someone explain how to fix it in step by step directions thanks i tried removing the error but it only created more errors if anyone could help i would appreciate it

//Entire code from this app is posted here.

the next line is where i am having trouble it says: unexpected '@' in program

```

This is an example of a not so smart question. First of all Mitchell does not even state what the error he is encountering in his code. Obviously people can not help him with his problem if he does not provide the problem in the first place. Second it sounds like he tried to fix his problem without understaind the actual problem behind it (evident from "removing the error but it only created more errors"). Lastly he does not punctuate correctly and hopes that people can fix the problem for him.


## Smart questions, a better way to learn
We all know that most people do not learn more effectively when they get handed the solution to problems. Coming up with questions yourself give you some sort of ground to learn from. Coming up with detailed and precise questions help the answerer answer in a helpful way too. For example the most upvoted answer to duplode's questions was a very detailed and thorough answer that combined picture visualizations and code examples to help him answer his question. On the contrary, people who look for answers on StackExchange (bad questions) do not learn as much because they are expecting other people to do their work for them without learning the steps on how to actually solve their own problem.
<p align="middle">
  <img src="../images/strong-questions.png" height="215" width="325"/>
</p>
