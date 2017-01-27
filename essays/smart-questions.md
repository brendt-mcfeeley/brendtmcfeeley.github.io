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

<img class="ui medium left floated image" src="../images/strong-questions.png">

## What is a smart question?
Everyone has heard the saying "There is no such thing as a stupid question." Most of us probably know someone that likes to ask dumb questions or have seen something online that make us do a mental double take. 
<p align="right">
  <img src="../images/simon.png" width="350"/>
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
A bad question is a question where the person jumps straight to the conclusion and wants answers right away without trying any other solutions out first. For example, someone is having trouble with their code and it does not work, this person then decides that instead of searching around on forums or looking at websties like StackOverflow for people that had similar problems, they deicde to hop on StackOverflow themselves and immedietly ask for help. 
without explaining that they have tried alternative methods but had failure.

For example in Java, C, and C++, declaring a variable is intuitive :

```
int x = 50;

float y = 40.5;

char z[5] = "hi" ;

```

But in JavaScript you only have three declaration types for all variables :

```
var intX = 50;

let y = 40.5;

const z = ["hi"]; //var, let, and const all have the same meaning, they only define how the variable can be used/modified

```

Althought it seems easier that there is only 1-3 types of initializers, it confuses me sometimes because it is ingrained in my mind to use int, float, etc. from the other languages that I learned before.


## My Thoughts on JavaScript in Software Engineering

I think JavaScript is an excellent language to learn in a Software Engineering course. It's a very simple language to use at the top level and it is a powerful language that is widely used. Many apps today are written in JavaScript so I feel that being able to keep up with modern times and adding a language like JavaScript to my list of languages will benefit me in the future. 

## Athletic Software Engineering (WODs)

ICS314 is the first class that introduced the workout of the day (WOD). Essentially it is a timed question to help students think critically on the spot. I think it is an amazing idea and I think most programming classes should implement this type of learning. The WOD is very stressful but it can simulate an enviornment simular to one at a job interview where the interviewer wants to see you answer a question on the fly. For example I was watching a mock Google interview put up by Google themselves and the interviewer watned the interviewee to answer the question and see his critical thinking process. I feel like the WOD can simulate this process extremely well and prepare people for future interviews.
