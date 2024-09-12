
# Assignment: Web Development Problems

This repository contains solutions to different problems related to web development. Below are the problems and their respective requirements.

---

### Problem 01: Tax Calculator

**Function Name:** `calculateTax()`

Harun, a successful hotelier, must calculate his monthly tax based on his income and expenses. You are tasked with writing a function calculating the tax as 20% of the difference between the monthly income and expenses.

**Function Requirements:**
- Input: 
  - `income`: A positive number representing the monthly income (0 <= income)
  - `expenses`: A positive number representing the monthly expenses (0 <= expense, and income >= expense)
- Output: 
  - The function should return the calculated tax. If the input is invalid, return the string `"Invalid Input"`.

**Sample Input:**
```js
calculateTax(10000, 3000)
```

**Sample Output:**
```js
1400
```

---

### Problem 02: Notification Generator

**Function Name:** `sendNotification()`

You need to write a function that generates a notification message using the `username` and `domain name` from an email.

**Function Requirements:**
- Input: A string `email` containing a valid email address.
- Output: A string in the format "`username` sent you an email from `domain name`". If the input is invalid (i.e., does not contain '@'), return the string `"Invalid Email"`.

**Sample Input:**
```js
sendNotification("zihad@gmail.com")
```

**Sample Output:**
```js
zihad sent you an email from gmail.com
```

---

### Problem 03: Checking Digits Inside a Name

**Function Name:** `checkDigitsInName()`

Raju needs help checking if a name contains digits. Write a function that checks if a string contains any numbers.

**Function Requirements:**
- Input: A string `name`.
- Output: 
  - Return `true` if the string contains numbers.
  - Return `false` if the string does not contain any numbers.
  - If the input is not a string, return `"Invalid Input"`.

**Sample Input:**
```js
checkDigitsInName("Raj123")
```

**Sample Output:**
```js
true
```

---

### Problem 04: Calculate Admission Final Score

**Function Name:** `calculateFinalScore()`

Rakib’s brother, Rajib, needs help calculating his final score for university admission. The final score is based on test score, school grade, and if the parent’s profession is a farmer.

**Function Requirements:**
- Input: An object with properties:
  - `name`: A string representing the student's name.
  - `testScore`: A number representing the test score (0 <= testScore <= 50).
  - `schoolGrade`: A number representing the school grade (0 <= schoolGrade <= 30).
  - `isFFamily`: A boolean representing whether the parent is a farmer (if true, add 20 points).
- Output: Return `true` if the final score is 80 or above, otherwise return `false`. If the input is invalid, return `"Invalid Input"`.

**Sample Input:**
```js
calculateFinalScore({ name: "Rajib", testScore: 45, schoolGrade: 25, isFFamily: true })
```

**Sample Output:**
```js
true
```

---

### Problem 05: Predict Average Waiting Time

**Function Name:** `waitingTime()`

Israt is waiting for a job interview, and she wants to know how much time it will take before she is called. Based on the interview times of those before her, calculate the average time and predict the remaining wait time.

**Function Requirements:**
- Input:
  - `waitingTimes`: An array of numbers representing the interview times for those who have already been interviewed.
  - `serialNumber`: A number representing Israt’s serial number.
- Output: 
  - Calculate the rounded average of the interview times.
  - Estimate how much time it will take for Israt to be called.
  - If the input is invalid, return `"Invalid Input"`.

**Sample Input:**
```js
waitingTime([3, 5, 7, 11, 6], 10)
```

**Sample Output:**
```js
24
```

---

### Important Note:
1. You must write all the logic and variables inside the function. Do not declare any global variables.
2. If you call a function or log anything to the console, delete or comment out that code before submission.
3. You must use the exact function names provided in the problem. Do not use different names.
4. Make sure to follow all problem requirements and return the specified values.
5. **No external help is allowed**. Do not use any AI tools or consult friends. Your assignment will be evaluated for originality.

--- 

**Author:** Abdul Jabbar Al Nahid

**License:** MIT

