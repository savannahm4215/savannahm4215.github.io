---
layout: post
title: "Flag Project-In Progess"
date: 2018-12-14
---

Welcome to Weekly Reflection #13, this week, we were required to once again to create a flag using Wescheme. The flag I had to create was the Pakistan flag and one question I had while creating this flag was how to make the cresent shape on my flag. However, I was able to figure out how to make the cresent shape while experimenting with two circles. Additionally, while doing this project some challenges I encountered was getting the star at the right angle and lining up the star and cresent. One more challenge I encountered was getting the flag the right color, however I was able to solve this by making my own color. Overall, creating my flag was relatively fun since I like working with the computer.

```(define SIZE (* 2 50 ))

(define GREEN( make-color 1 65 28))

(define REC (rectangle (* 3 150) (* 3 100) "solid" GREEN ))

(define CIR1 (circle SIZE "solid" "white" ))

(define CIR2 (circle SIZE "solid" GREEN))

(define STAR (rotate 100 (star (* 5 7) "solid" "white" )))

(define FLAG (rectangle (* 2 250) (* 2 150) "outline" "black"))

(put-image STAR 365 200(put-image CIR2 340 175 (put-image CIR1 310 150 (put-image REC 350 150 FLAG))))```
   


![FlagV2](/images/FlagV2.png)
