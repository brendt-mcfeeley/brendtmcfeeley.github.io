---
layout: essay
type: essay
title: Final Project Idea
date: 2017-03-09
labels:
  - Software Engineering
  - Meteor
---

# Overview

The Problem : The Department of Engineering sends out too many daily emails to students about upcoming events, clubs, seminars (with guest speakers), fundraisers, scholarships (directed to engineering majors), and faculty forms. Students usually ignore a lot of the emails they get from the university because they think it's spam or not relevent to think and they miss out on a lot of important events and/or imformation.

The Solution : We will create an app centralizes all events organized by clubs and faculty and create a calender for pretty reasons. Club officers and faculty will have access to add, edit, and remove events and information on the app. Anyone with a valid UH email will be able to register and get information for the app as well. Users will be able to "favorite" clubs or certain announcement and receive notifcations for the updates. The user will be able to RSVP via the app so there is an about accurate headcount of how many people will attend.

# Mockup Pages

* Public Landing Page
* Login Page
* User Homepage
* Admin Homepage (general)
* Club Admin Homepage
* Calender
* Chronological list of events coming up 

# Case Ideas



# Beyond the Basics

# What is Meteor?

[Meteor](https://www.meteor.com/) is a powerful free and open-source JavaScript web framework. One of the main featues of Meteor is it's ability to quickly prototype the web application you are building and it produces cross-platform code (for Android, iOS, Web, etc.).  

# My Past Problem

I'm not going to lie, I've only completed 2/7 parts of my Digits assignment as of writing this essay so I have not had any major problems, only minor ones. The only problem I've had so far was in the very beginning of Digits, part 2 which was to add a new page and route/index to it with a button.

My problem was when I was adding the code to the index.js file. I accidently overwrote code that linked all the pages together so none of my pages started to show up. I was freaking out about what I did but I realized I was not that far into my code. I revereted it back to the base code and took it step by step and realized that I did not add new code to my index.js file to import my add-contact-page.html but rather I overwrote existing code that was crucial to the web application.

In the wise words of Philip Johnson :
> If you carefully construct your template yet nothing shows up, the first thing you should think to yourself is darn I forgot to import it.

And that is exactly what I did not do, I did not import my add-contact-page.html correctly and I suffered maybe 5-10 mintues trying to fix it. **Always remember to index your pages!**

# My Current Problem

One of the biggest problems I've had with the "Digits" Meeteor assignment in my Software Engineering class is having all my routing pages work at once. 

The code the router.js file looks like :

```
FlowRouter.route('/', {
  name: 'Home_Page',
  action() {
    BlazeLayout.render('App_Body', { main: 'Home_Page' });
  },
});

FlowRouter.route('/add-contact', {
  name: 'Add_Contact_Page',
  action() {
    BlazeLayout.render('App_Body', { main: 'Add_Contact_Page' });
  },
});

FlowRouter.route('/edit-contact/:id', {
  name: 'Edit_Contact_Page',
  action() {
    BlazeLayout.render('App_Body', { main: 'Edit_Contact_Page' });
  },
});
```

At first I was not able to get my page at localhost:3000/add-contact to work, but that was because I edited another route and accidently overwrote it with the add contact route. Now I can see my add contact and edit contact route but now I am not able to see my home-page.html. I have not changed anything regarding my homepage in the application yet it does not show up. I checked out the routing, template, and indexing page and all of them have the correct code in order for a page to show up but so far I have not gotten it to work. 
