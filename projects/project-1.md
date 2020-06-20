---
layout: project
type: project
image: images/secure.png
title: Secure Account
permalink: projects/secure
date: 2016
labels:
  - HTML/CSS
  - Hashing
  - Javascript
  - PHP
  - SQL
  - GitHub
summary: A secure account database with password hashing that my team developed in ICS 491.
---

Secure Account is a web application phonebook that I helped create as a team project in ICS 491, Summer 2016. The project helped me learn how to implement a database with login functions that hash passwords to prevent hackers from easily accessing private information. I also learned how to perform static and dynamic analysis, including fuzz testing to check for vulnerabilities in our code and application.

Secure Account is implemented using [Twitter Bootstrap](https://getbootstrap.com/) for front-end user login interface and [MongoDB](http://mongodb.com) for the phonebook database. We wanted a secure login that would not be broken into through brute force, so we implemented some javascript functions to check for account information. Password protection was implemented through a hashing + salting algorithm [CSPRNG](https://www.php.net/manual/en/function.openssl-random-pseudo-bytes.php) in PHP.

In this project I gained experience with full-stack web application design and associated technologies, including [MongoDB](http://mongodb.com) for database storage, the [Twitter Bootstrap](http://getbootstrap.com/) CSS Framework for the user interface, and Javascript for both client and server-side programming. I also had exposure to password and database security through the discussed hashing and salthing methods.
 
Source: <a href="https://github.com/qu-leon/ics491"><i class="large github icon"></i>secureAccount/secure</a>
