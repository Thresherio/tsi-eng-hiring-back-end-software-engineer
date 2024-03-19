# Challenge: Happy Number

This coding challenge is meant to evaluate how a back-end software engineer approaches a problem and works through it. You can use your language of choice, and any resources you would normally use to do your job (Google, StackOverflow, documentation, etc.). The only disallowed action is looking up the exact problem and copy/pasting a solution. The challenge is intended span 30-60 minutes, and the focus is not on whether you have a complete working solution in the time period, but instead on how you worked through the problem.

## Part I

A number is happy if it eventually leads to `1` after a sequence of steps is performed, where in each step, *the number is replaced by the sum of the squares of its digits.*

* Write a function that takes a positive integer, and returns a boolean indicating whether the supplied integer is happy or not. 
* Feel free to break out the code into multiple functions as necessary.

**Examples/Test Cases:**

```python
a = 100  # 1^2 + 0^2 + 0^2 = 1 => true
b = 13  # 1^2 + 3^2 = 10 => 1^2 + 0^2 = 1 => true
c = 7  # 7^2 = 49 => 4^2 + 9^2 = 97 => 9^2 + 7^2 = 130 => 1^2 + 3^2 + 0^2 ... => true
d = 4 # 4^2 = 16 => 1^2 + 6^2 = 37 => 3^2 + 7^2 = 58 => 5^2 + 8^2 = 89 => 8^2 + 9^2 = 145 => 1^2 + 4^2 + 5^2 = 42 => 4^2 + 2^2 = 20 ... 4 => false
```

## Part II

Now that you've built this prototype, if you were told to *"Turn this into a production-ready app"*, what would your process look like?

* Describe key considerations.
* Discuss development approach.
* Discuss scalability.
* Review the code you wrote in Part I begin making relevant changes.
