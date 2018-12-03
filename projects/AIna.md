---
layout: project
type: project
image: images/aina/ainaSquare.png
title: AI.na
permalink: projects/AIna
date: 2018
labels:
  - TensorFlow
  - Android
  - Java
  - Firebase
  - Machine Learning
summary: Utilize machine learning to identify native Hawaiian plants.
---

<p align="center">
  <img  src="../images/aina/ainaLogo.png">
</p>

# What is AI.na?

[AI.na](https://devpost.com/software/guccigang) is an mobile application that utilizes [TensorFlow Lite](https://www.tensorflow.org/lite/) machine learning to help identify rare and native plant species in Hawai'i. It was built for the [Honolulu Annual Code Challenge](http://hacc.hawaii.gov/), a month long hackathon that helps promote technology solutions within the government. With the help of my team, we were able to achieve second place for this competition.

Check out the [GitHub Repository!](https://github.com/brendtmcfeeley/AI.na)

# Why do we need a mobile plant identifier?

The challenge was initially proposed by [KUPU](http://www.kupuhawaii.org/) and the [Department of Land and Natural Resources](https://dlnr.hawaii.gov/), who needed an accessible way to help them identify native Hawaiian plants. Hawaii's native plants are unique, culturally important, and many are critically endangered and it is important that we help preserve our rich cultural history with technology. There currently no plant identification applications that cater towards native Hawaiian plants, and we wanted to help create the solution by digitizing an identification system. With the help of the users, our application grows better and larger because the users have the power to help train our machine learning model.

# How we Built our Application

The basis of our application revolved our TensorFlow, which is an open source machine learning library. We were able to train our machine learning model on 500-1000 images for each type of flower then transform the graph into a mobile optimized graph using TensorFlow Lite, which helped us keep the performance of our application optimal. This also means that we can push updated machine learning models to phones through updates, reducing the need to train actual graphs on mobile devices. We built an android application around TensorFlow Lite, making sure to keep the UI process steamlined and easy to use. We followed Google's [Material Design Standards](https://material.io/design/) to ensure our application is modern and expressive.

## Application Overview

<p align="center">
    <iframe width="560" height="315" src="https://youtu.be/Bln2W999FxA" frameborder="0" allowfullscreen></iframe>
</p>