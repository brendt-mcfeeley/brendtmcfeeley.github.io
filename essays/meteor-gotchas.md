---
layout: essay
type: essay
title: Meteor Gotchas
date: 2017-03-09
labels:
  - Software Engineering
  - Meteor
---

# What is Meteor?

[Meteor](https://www.meteor.com/) is a powerful free and open-source JavaScript web framework. One of the main featues of Meteor is it's ability to quickly prototype the web application you are building and it produces cross-platform code (for Android, iOS, Web, etc.).  

# The Biggest Problem I've Solved

# The Biggest Problem I Have

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
