---
layout: post
title:  Statiscally Regularities
date: 2023-05-16 21:01:00
description: Randomness may not be random for large number of experiment
tags: Math
# categories: Learning stuff
# thumbnail: assets/img/fourier.jpg
giscus_comments: true
---

## A modified dice game
When we roll a dice we can't say what will be the outcome but what can we say that out of {1, 2, 3, 4, 5, 6} any one will be the outcome.So obviously this is random process. Now let modified the dice. It has **four faces** from 1 to 4 for sake of problem(or rather a pattern).

## How to get the radomness in computer
It is computer each and every machinary is work on a algorithm. Purely random number is never possible at least in this classical computer. So random number in computer is nothing but pseudo random number it is based on some unknown algorithm. There is some kind of **seed** which generate a particular pattern of random number. As we will use `python` in-buit command to generate random number for now we can forget about how to generate random number which will obey some distribution. 

## Random experiment can give you a regular pattern
To get beutiful pattern we going to use simple our cartesian plane. Let's say we start from origin i.e, $$(x = 0, y = 0)$$  roll the modfied die to see the *random* output and it will tell us what will be next step of moving our pen. 
If face of the die is 1 we will move to 
\begin{equation}
(0.8x + 0.1, 0.8y + 0.04)
\end{equation}
if the face is 2 we will move to 
\begin{equation}
(0.5x + 0.25, 0.5y + 0.4)
\end{equation}

## Lets progarm it

## Other such pattern


<!-- bundle exec jekyll serve -->