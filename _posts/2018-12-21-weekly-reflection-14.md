---
layout: post
title: "Flag Project - Final Submission"
date: 2018-12-21
---

## Flag of Pakistan by Savannah 

## Description of my program

-   I designed the Pakistan Flag using Wescheme. At first, I thought I would have trouble doing this project but it turned out great.
-   I expect at least a 3 on this project because although the Pakistan flag is Professional/4 level, I believe that I could've done better on this project. Therefore, I feel like I at least deserve a Practitioner on this flag project. 


## Current output

* * *
![Flag](/images/FlagV2.png)
* * *

## Description of my process

- One strategy one of my classmates gave to me was to use two circles to create the cresent on my flag. That strategy helped me out tremendously while making the Pakistan flag.
- One question I had was how can I make the flag the same color as the actual Pakistan flag?

## Explanation of my code

-   The argument "CIR2" helped me halfway create the cresent needed for my flag to be complete. While, the argument "STAR" helped me create the star needed for the Pakistan flag, also it helped me get the star at the right angle. The argument "FLAG" helped create the base needed for my flag's width and height.

* * *

```(define CIR2 (circle SIZE "solid" GREEN))

(define STAR (rotate 100 (star (* 5 7) "solid" "white" )))

(define FLAG (rectangle (* 2 250) (* 2 HEIGHT) "outline" "black"))

(put-image STAR 365 200(put-image CIR2 340 175 (put-image CIR1 310 HEIGHT (put-image REC 350 HEIGHT FLAG))))```

* * *


## Program code

```(define SIZE (* 2 50 ))

(define HEIGHT ( * 5 30))

(define GREEN( make-color 1 65 28))

(define REC (rectangle (* 3 150) (* 3 100) "solid" GREEN ))

(define CIR1 (circle SIZE "solid" "white" ))

(define CIR2 (circle SIZE "solid" GREEN))

(define STAR (rotate 100 (star (* 5 7) "solid" "white" )))

(define FLAG (rectangle (* 2 250) (* 2 HEIGHT) "outline" "black"))

(put-image STAR 365 200(put-image CIR2 340 175 (put-image CIR1 310 HEIGHT (put-image REC 350 HEIGHT FLAG))))```


  <style>
        h1 {
            color: rgb(255, 255, 255);
        }
        body {
            background-color: rgb(172, 0, 245);
        }
        </style>

