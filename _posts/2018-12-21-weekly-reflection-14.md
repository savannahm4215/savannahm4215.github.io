---
layout: post
title: "Flag Project - Final Submission"
date: 2018-12-21
---

## Flag of Pakistan by Savannah 

## Describe your program

-   I designed the Pakistan Flag using Wescheme
-   I expect at least a Practitioner on this project 


## Current output

* * *
![Flag](/images/FlagV2.png)
* * *

## Describe your process.

- One strategy one of my classmates gave to me was to use two circles to create the cresent on my flag
- One question I had was how can I get 

## Explain your code.

-   Choose a significant part of your program (15 lines max) and paste it below. Do not insert your entire program here. _then delete this instruction_
-   Explain each argument in the code section. _then delete this instruction_
-   Tell us how it functions independently and within the whole program _then delete this instruction_

* * *

```
Insert 10-15 line code section here _then delete this instruction_
```

* * *

-   Explain the code you posted by telling us about each argument.
-   Then tell us how your code section fits into the whole.
 
<!--- Delete this comment and add your writing -->


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
