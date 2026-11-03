# Definition
- This is the way to measure how fast or slow an algorithm runs as the amount of input data increases

## Ways to measure time complexity
- Best Case
- Average Case
- Worst Case

- we focus on the worst case and use the Big O Notation because it is independent of the machine, that means we are testing the code not the machine specifics.

- The Big O notation has complexities like 
    - O(1) : This is the best one because the  amount of time it takes is constant throughout.
    - O(n) 
    - O(logn)
    - 0(nlogn)
    - 0(n^2)

## Consider the code below

```js
const a = 1;
const b = 2;
const sum = a + b;

// In this code, each operation runs one time, that is the 0(1) and it runs three times, 
// ie 3 *  O(1) and we igore the constants to have the complexity as a O(1)
```

- For loops, not nested, the time complexity becomes O(n) because the loop runs n times
- Then for nested loops, it becomes O(n^2)


## Summary of Time Complexity

In this lesson we learned all about Time complexity.

Time complexity is a way to measure how long an algorithm takes to run as the amount of input data increases.

We learned about how to find time complexity by counting the number of operations performed in an algorithm.

We also learned about two rules of finding time complexity of an algorithm

    Ignore constants
    Focus only on the largest factor

We ignore constants when finding the final time complexity. Also, if there are multiple pieces of an algorithm with varying time complexity, we only take the largest factor.

We also learned how to calculate time complexity of nested loops.

In the next lesson we will see how we have to break the Rule 2 sometimes and also how to apply time complexity to DSA problems in general.

Then we will practice a lot of problems on finding time complexity.