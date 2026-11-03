## Time complexity for DSA

Let's go through some examples to understand how to use time complexity for programming problems.

Say you calculate the sum of numbers from 1 to N using the following algorithm

``` py
sum = 0
for i = 1 to N
    sum += i
print(sum)
```
and the constraints on N are:

```bash 
1≤N≤1001≤N≤100
```

Will the above algorithm run within 1 second?

### Lets work this out 
A standard computer performs 10^8 operations per second
First operation is O(1)
Second operation is O(N) for the loop and the max is 100, 
So this means that the loop maximumly can run up to 100 operations, which is less that the 10^8 operations
And yes this can be executed in a second.