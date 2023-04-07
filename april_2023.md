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
- [x] **Planning of the sixth interview.**
- [x] **Identify an individual for the seventh interview.**
- [ ] **Planning of the seventh interview.** → *In progress*

### Svelte !

- [ ] 1. **Introduction** -> *In progresss*
- [ ] 2. **Reactivity**
- [ ] 3. **Props**
- [ ] 4. **Logic**
- [ ] 5. **Events**
- [ ] 6. **Bindings**
- [ ] 7. **Life cycle**
- [ ] 8. **Stores**
- [ ] 9. **Mention**
- [ ] 10. **Transitions**
- [ ] 11. **Animations**
- [ ] 12. **Actions**
- [ ] 13. **Advanced styling**
- [ ] 14. **Component composition**
- [ ] 15. **Context API**
- [ ] 16. **Special Elements**
- [ ] 17. **Module context**
- [ ] 18. **Special tags**
- [ ] 19. **Next steps**
- Total Progression → __0%__

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

#2023-04-06
---------------------------------------------------------
    
### Codecademy Back-End Engineer courses achievements !
Daily course achievements goals track.

- [ ] **Open-Ended Project** → *In progress*
- Total Progression → __99%__

### Project on going !

__Title:__ Codecademy project: Open-Ended Project

- [ ] **"Resource and Plan Development for AI-Regulatory_assistant"** → *In progress*
- [x] **Identify an individual for the fifth interview.**
- [x] **Planning of the fifth interview - scheduledFriday on the 7th of April 2023**
- [x] **Planning of the sixth interview - scheduledFriday on the 7th of April 2023**
- [x] **Planning of the seventh interview - scheduledFriday on the 14th of April 2023**

### Svelte !

- [x] 1. **Introduction** 
- [x] 2. **Reactivity** -> *In progresss*
- [ ] 3. **Props**
- [ ] 4. **Logic**
- [ ] 5. **Events**
- [ ] 6. **Bindings**
- [ ] 7. **Life cycle**
- [ ] 8. **Stores**
- [ ] 9. **Mention**
- [ ] 10. **Transitions**
- [ ] 11. **Animations**
- [ ] 12. **Actions**
- [ ] 13. **Advanced styling**
- [ ] 14. **Component composition**
- [ ] 15. **Context API**
- [ ] 16. **Special Elements**
- [ ] 17. **Module context**
- [ ] 18. **Special tags**
- [ ] 19. **Next steps**
- Total Progression → __10.5%__

### Codewars Kata !

__Description:__

>ATM machines allow 4 or 6 digit PIN codes and PIN codes cannot contain anything but exactly 4 digits or exactly 6 digits.
>
>If the function is passed a valid PIN string, return true, else return false.
>
>Examples (Input --> Output)

````shell
"1234"   -->  true
"12345"  -->  false
"a234"   -->  false
````
__My solution:__

>My first thought was to use the handy `parseInt()` function. As I was testing my code, I noticed that the function wasn't working properly. The error message indicates that the test case for the input "0000" failed because the function returned false instead of true. This happened because the `parseInt()` function treats leading zeros as octal notation, so "0000" gets converted to the number 0. Therefore, the `Number.isInteger()` check fails and the function returns false.
````js
function validatePIN(pin) {
    const num = parseInt(pin);
    if(Number.isInteger(num) && (pin.length === 4 || pin.length === 6) && num > 0) {
      return console.log(true);
    } else {
      return console.log(false);
    }
};
````
Terminal output error:
````shell
Test Results:
validatePIN
  should return False for pins with length other than 4 or 6
  should return False for pins which contain characters other than digits
  should return True for valid pins
    Wrong output for '0000': expected false to equal true
````
>I knew I needed a different approach. With the help of regex, I was able to write a function that correctly converted strings into integers without any issues.
````js
function validatePIN(pin) {
  const regex = /^\d+$/;
  if(regex.test(pin) && (pin.length === 4 || pin.length === 6)) {
    return true;
  } else {
    return false;
  }
};
````
>The `validatePIN()` function takes a string argument pin.
>
>The regular expression `^\d+$` is stored in the regex variable. This regular expression matches a string that contains only digits `(0-9)` and no other characters.
>
>The `test()` method of the regex object is called with the pin argument as its parameter. This method returns true if the pin string matches the regular expression, and false otherwise.
>
>The if statement checks if the pin string matches the regular expression and if its length is either `4` or `6` characters. If both conditions are true, the function returns true.
>
>If the if statement condition is not met, the function returns false.
>
>In summary, the `validatePIN()` function checks whether the pin string contains only digits and has a length of either `4` or `6` characters. If both conditions are met, the function returns true. Otherwise, it returns false.
>
Refactored version:
````js
function validatePIN(pin) {
  const regex = /^\d{4}(\d{2})?$/;
  return regex.test(pin);
}
````
>The regular expression `^\d{4}(\d{2})?$` is used to match PINs that are either `4` or `6` digits long.
>
>The `{4}` quantifier matches exactly four digit characters, and the `(\d{2})?` group matches an optional sequence of two more digit characters.
>
>The `^` and `$` anchors match the beginning and end of the string, respectively.
>
>The `test()` method of the regular expression object is used to check if the input pin matches the regular expression.
>
>The function returns true if the pin matches the regular expression, and false otherwise.

### Other !

>Today, I didn't feel like summarizing a 10,000-word text, so I asked ChatGPT to do it for me. However, ChatGPT can only process requests containing 1000-1300 words at a time. To work around this limitation, I split the text into multiple files containing 1000 words each and instructed ChatGPT to wait for further instructions. I wrote a small script to split the text into these files. Finally, I asked ChatGPT to summarize all the information I had given it.

````powershell
>$wordCount = (Get-Content file.txt | Measure-Object -Word).Words
>echo "Word count: $wordCount"
>powershell -Command "& {$(($wordCount) * 0.25)}"
Word count: 10162
````

````powershell
$InputFile = ".\file.txt"
$OutputFilePrefix = ".\outputfile"
$MaxWords = 1000
$WordCount = 0
$FileCount = 1

Get-Content $InputFile -ReadCount 1 -Encoding UTF8 | ForEach-Object {
    $Line = $_
    $Words = $Line -split '\s+'
    foreach ($Word in $Words) {
        if ($WordCount -eq 0) {
            $OutputFile = $OutputFilePrefix + "_$FileCount.txt"
            $FileCount++
        }
        Add-Content $OutputFile $Word -NoNewline
        Add-Content $OutputFile ' ' -NoNewline
        $WordCount++

        if ($WordCount -ge $MaxWords) {
            $WordCount = 0
        }
    }
}
````

#2023-04-06
---------------------------------------------------------
    
### Codecademy Back-End Engineer courses achievements !
Daily course achievements goals track.

- [ ] **Open-Ended Project** → *In progress*
- Total Progression → __99%__

### Project on going !

__Title:__ Codecademy project: Open-Ended Project


### Svelte !

- [x] 1. **Introduction** 
- [x] 2. **Reactivity**
- [x] 3. **Props**
- [x] 4. **Logic**
- [ ] 5. **Events** -> *In progresss*
- [ ] 6. **Bindings**
- [ ] 7. **Life cycle**
- [ ] 8. **Stores**
- [ ] 9. **Mention**
- [ ] 10. **Transitions**
- [ ] 11. **Animations**
- [ ] 12. **Actions**
- [ ] 13. **Advanced styling**
- [ ] 14. **Component composition**
- [ ] 15. **Context API**
- [ ] 16. **Special Elements**
- [ ] 17. **Module context**
- [ ] 18. **Special tags**
- [ ] 19. **Next steps**
- Total Progression → __10.5%__

### Codewars Kata !

__Description:__

>You might know some pretty large perfect squares. But what about the NEXT one? Complete the findNextSquare method that finds the next integral perfect square after the one passed as a parameter. Recall that an integral perfect square is an integer n such that sqrt(n) is also an integer. If the parameter is itself not a perfect square then -1 should be returned. You may assume the parameter is non-negative.

Examples:(Input --> Output)
````
121 --> 144
625 --> 676
114 --> -1 since 114 is not a perfect square
````
__My solution:__

````javascript
function findNextSquare(sq) {
  let root = Math.sqrt(sq);
  while (!Number.isInteger(root)) {
    return -1;
  }
  root++;
  return root ** 2;
}
````

````javascript
function findNextSquare(sq) {
  root = Math.sqrt(sq)
  if(Number.isInteger(root)) {
    root++
    return root ** 2;
  } else {
    return -1 ;
  }
};
````

Refactored version:
````javascript
function findNextSquare(sq) {
  const root = Math.sqrt(sq);
  return Number.isInteger(root) ? (root + 1) ** 2 : -1;
}
````