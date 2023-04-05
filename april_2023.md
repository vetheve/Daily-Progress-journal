---
layout: default
title: April 2023
description: This is just another page
---

Daily Progress Journal
======================

"Tracking My Progress: Daily Journaling to Achieve Goals"

* **April 2023**

|Mon  |Tue  |Wed  |Thu  |Fri  |Sat  |Sun  |
|---:|---:|---:|---:|---:|---:|---:|
|     |     |     |     |     | 1 | 2 |
|[3](#2023-04-03)|[4](#2023-04-04)|[5](#2023-04-05)|[6](#2023-04-06)|[7](#2023-04-07)| 8 | 9 |
|[10](#2023-04-10)|[11](#2023-04-11)|[12](#2023-04-12)|[13](#2023-04-13)|[14](#2023-04-14)| 15 | 16 |
|[17](#2023-04-17)|[18](#2023-04-18)|[19](#2023-04-19)|[20](#2023-04-20)|[21](#2023-04-21)| 22 | 23 |
|[24](#2023-04-24)|[25](#2023-04-25)|[26](#2023-04-26)|[27](#2023-04-27)|[28](#2023-04-28)| 29 | 30 |


#2023-04-03
---------------------------------------------------------
    
### Codecademy Back-End Engineer courses achievements !
Daily course achievements goals track.

- [ ] **Interviewing in the Tech Industry: Behavioral Interviews** → *In progress*
- [ ] **How to Succeed in A Behavioral Interview**
- Total Progression → __99%__

### Project on going !

__Title:__ Codecademy project: Photo Caption Contest

- [x] **Plan the project**
- [x] **Define endpoints**
- [x] **Setup the environment**
- [x] **Create the models**
- [x] **Create the seeders**
- [x] **Create the controllers**
- [x] **Create the auth middleware to specific endpoints** → *In progress*
- [x] **Create the routes**
- [x] **Test the endpoints**
- [x] **Configure localized caching**
- [x] **Write a swagger documentation**
- Total Progression → __100%__

__Last commits:__

- **""ADD: swagger file""**

__Title:__ Codecademy project: Open-Ended Project

- [ ] **"Resource and Plan Development for AI-Regulatory_assistant"** → *In progress*
- [x] **I completed my fourth interview today with Aurore F.**
- [ ] **Identify an individual for the fourth interview.** → *In progress*

#2023-04-04
---------------------------------------------------------
    
### Codecademy Back-End Engineer courses achievements !
Daily course achievements goals track.

- [x] **Interviewing in the Tech Industry: Behavioral Interviews**
- [x] **How to Succeed in A Behavioral Interview**
- Total Progression → __99%__

### Project on going !

__Title:__ Codecademy project: Open-Ended Project

- [ ] **"Resource and Plan Development for AI-Regulatory_assistant"** → *In progress*
- [x] **Identify an individual for the fifth interview.**
- [ ] **Identify an individual for the sixth interview.** → *In progress*

#2023-04-05
---------------------------------------------------------
    
### Codecademy Back-End Engineer courses achievements !
Daily course achievements goals track.

- [ ] **Open-Ended Project** → *In progress*
- Total Progression → __99%__

### Project on going !

__Title:__ Codecademy project: Open-Ended Project

- [ ] **"Resource and Plan Development for AI-Regulatory_assistant"** → *In progress*
- [x] **Identify an individual for the fifth interview.**
- [x] **Planning of the fifth interview.**
- [x] **Identify an individual for the sixth interview.**
- [x] **Planning of tthe sixth interview.**
- [x] **Identify an individual for the seventh interview.**
- [ ] **Planning of tthe sixth interview.** → *In progress*

### Codewars Kata !

__Description:__

>Some numbers have funny properties. For example:
>
>89 --> 8¹ + 9² = 89 * 1
>
>695 --> 6² + 9³ + 5⁴= 1390 = 695 * 2
>
>46288 --> 4³ + 6⁴+ 2⁵ + 8⁶ + 8⁷ = 2360688 = 46288 * 51
>
>Given a positive integer n written as abcd... (a, b, c, d... being digits) and a positive integer p
>
>we want to find a positive integer k, if it exists, such that the sum of the digits of n taken to the successive powers of p is equal to k * n.
>In other words:
>
>Is there an integer k such as : (a ^ p + b ^ (p+1) + c ^(p+2) + d ^ (p+3) + ...) = n * k
>
>If it is the case we will return k, if not return -1.
>
>Note: n and p will always be given as strictly positive integers.
````js
digPow(89, 1) should return 1 since 8¹ + 9² = 89 = 89 * 1
digPow(92, 1) should return -1 since there is no k such as 9¹ + 2² equals 92 * k
digPow(695, 2) should return 2 since 6² + 9³ + 5⁴= 1390 = 695 * 2
digPow(46288, 3) should return 51 since 4³ + 6⁴+ 2⁵ + 8⁶ + 8⁷ = 2360688 = 46288 * 51
````
__My solution:__

````js
function digPow(n, p) {
  // Convert the number to an array of digits
  const numArray = Array.from(String(n), Number);

  // Calculate the sum of each digit raised to the power of p + its position in the number
  const sumPow = numArray.reduce((accumulator, currentValue, index) => 
    accumulator + Math.pow(currentValue, p + index), 0);

  // If the sum is divisible by n, return the result, otherwise return -1
  return sumPow % n === 0 ? sumPow / n : -1;
}
````
