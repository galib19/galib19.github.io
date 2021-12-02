---
title: "LifeBlood"
collection: projects
permalink: /projects/LifeBlood2018
excerpt: 'This research project analyzes pre-birth factors, such as birth history, maternal history, reproduction history, socio-economic condition, etc. for the early classification of child mortality. Manuscript in Preparation.'
#date: '2019-06-03'
#venue: 'In Proceedings of the 32nd International Conference on Software Engineering Knowledge Engineering, 2020 (SEKE 2020)'
#paperurl: 'http://galib19.github.io/files/SigAPI_SEKE_2020.pdf'
#citation: 'Galib, A. H., Hossain, B. M. (2020, July). Significant API Calls in Android Malware Detection (Using Feature Selection Techniques and Correlation Based Feature Elimination). In Proceedings of the 32nd International Conference on Software Engineering Knowledge Engineering (pp.566-571).'


---

[[Github]](https://github.com/galib19/LifeBlood)

“LifeBlood” is an android app for simplifying blood donation system. It is an GPS based blood donor finder android app which sorts out nearer blood donors across the map. In addition, a user rating system and profiling of donors are being implemented. This system includes the following:   

## Registration

A new user can sign up by giving the following information: username, password, name, age, mobile number, address and blood group. System check whether the username is unique. After successful registration a new profile will be created. By default, a user is a receiver as well as a donor who can make request for blood. She can also become only a blood receiver by activating it after registration.

## Authentication

User can log in to her account using email and password. And she also can log out from her account at any time.

## User Profile

User profile holds the details of that user. This contains user details, profile image, name, blood group, phone number and email id. Any user can update his profile data any time.

## Receiver

Receiver is one who receives blood from donor. S/he can make a blood request of urgent blood. S/he can also acknowledge some specific issues like hospital name, request details and blood group via that request. This request will search through the customized map to sort out nearer donors of that desired blood group. This list is sorted according to distance. Then it shows all the neared donor list and markers on map. Receiver will then connect to any specific donor via phone call.

## Donor

Donor is one who donates the blood. A user is by default a blood receiver as well as a donor. Any user can deactivate his donorship by deactivating it. Then h/she only receive blood but not act as a donor.

## Map

Any user can view his/her current location on map. Besides when a blood request raised, all nearer donors’ position is being marked on the map. This is a custom maker which also holds the user profile image and distance.