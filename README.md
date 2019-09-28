# CS50 Love (Final Project)
**by Zach CHAN**

![](https://icon-library.net/images/love-icon-png/love-icon-png-14.jpg)


**Table of Contents**

<!-- TOC depthFrom:2 -->

- [Introduction](#introduction)
- [Dependencies](#dependencies)
- [Basic Workflow](#basic-workflow)
- [Screenshots](#screenshots)
- [About the author](#about-the-author)

<!-- /TOC -->


# Introduction
This is CS50 Love. 

Github Page for Issuing Bugs: https://github.com/zach1king/cs50-love

This web app is written in Python with Flask Framework. Under the inspiration of ```CS50 Finance``` app, ```CS50 Love``` is developed using CS50 IDE, aiming to introduce lovers to those are single.

The app aims to be free so that people from worldwide can meet and chat without any payment. However, to support, a donate function is added onto the website as well.


CS50 Love Website URL: https://shchanam.pythonanywhere.com

# Dependencies
Before running the web app in CS50 IDE, please run the following in the console:
```shell
sudo pip install Flask-SQLAlchemy
sudo pip install pycountry
sudo pip install apscheduler
```
Additional Dependenies: Flask SQLAlchemy, pycountry, aspscheduler

Database: love.db,
Tables:
1. users (for storing user info)
2. transfer (for recording users interactions)
3. countries (READ-ONLY: dictionary for mapping locations and dial number headers)

# Basic Workflow
1. Registrant (new user)
![](https://i.imgur.com/jjsDiFG.jpg)
2. Requester
![](https://imgur.com/NhyrazD.jpg)
3. Confirmer
![](https://imgur.com/MYHpH0R.jpg)

# Screenshots
(IMG-1)	Zach's Profile
![](https://i.imgur.com/FMvQn0y.jpg)

(IMG-2) Register Page
![](https://i.imgur.com/qWJcdwA.jpg)

(IMG-3) Login Page
![](https://i.imgur.com/kT1q99k.jpg)

(IMG-4) Role: Requester, Step 1: Browse
![](https://i.imgur.com/83riGjN.jpg)

(IMG-5) Role: Requester, Step 2: See Profiles
![](https://i.imgur.com/zL8f3DJ.jpg)

(IMG-6) Role: Requester, Step 3: Send love
![](https://i.imgur.com/iS8n452.jpg)

(IMG-7) Role: Requester, Step 4: Love is sent!
![](https://i.imgur.com/jPQ9Q5I.jpg)

(IMG-8) Role: Requester, Step 5: History Tab shows Pending...
![](https://i.imgur.com/pcZkPFx.jpg)

(IMG-9) Role: Confirmer, Step 1: Login
![](https://i.imgur.com/SkEwOzR.jpg)

(IMG-10) Role: Confirmer, Step 2: See Confirm Tab
![](https://i.imgur.com/OnDmmYF.jpg)

(IMG-11) Role: Confirmer, Step 3: See Love Message
![](https://i.imgur.com/iEkKyzu.jpg)

(IMG-12) Role: Confirmer, Step 4: Accept
![](https://i.imgur.com/uWK7X0J.jpg)

(IMG-13) Role: All, Step 5: History Tab shows Whatsapp Number
![](https://i.imgur.com/bzDQ5zg.jpg)


# About the author
---by Zach CHAN on 27 Sep, 2019

I am a programmer from Hong Kong and the creator of CS50 Love. I studied CS50 2018 in September, 2019 through edX.

I am desperate for love and also want to help to change the world, to a world full of love. This is the initiate to CS50 Love website.

CS50 is an excellent Computer Science course for beginners, organised by the Harvard University. This website is my Final Project in this course. Go edX.org to find out the courses designed for you.

Since the website is still in development, many of the features are not yet added. Sorry for any inconvenience course.

Please find my contact information on my Patreon profile, which can be found in the "Donate" Tab of CS50 Love website to give suggestions on improvements to the website. Thank you very much for your support.

My Patreon Website: https://www.patreon.com/zachchan

To make this app happen, I need to thank all CS50 staff for their teaching and support. Thank you, David J. Malan, without your inspiration, I don't think I can have such an ability to create this simple but amazing app.

I love CS50 3000!
