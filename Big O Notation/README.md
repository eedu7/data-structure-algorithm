# What is Big O?
Big O is the language and metric we use to describe the efficiency of algorithms.

> `Time Complexity`: A way of showing how the runtime of a function increases as the size of input increases
> - In time complexity, we don't measure how much time it took to run a program, as the slower program will run much faster on a super fast computer,
>   So, we measure the `number of operations`

> `Space Complexity`: the amount of memory required by an algorithm to solve a problem, which is influenced by the population size and problem dimension.

### Types of Runtime:
- O(N)
- O($N^2$)
- O($2^N$)
- Time Complexity: O(wh)

## Big O Notations
- Best Case
- Average Case
- Worst Case

> Big O: It is a complexity that is going to be less or equal to the worst case <br>
> Big - &Omega; It is a complexity that is going to be at least more than the best case <br>
> Big - &Theta;: It is a complexity that is within bounds of the worst and the best cases.

## Runtime Complexity
| Complexity | Name        | Sample                           | Description                                                                                                                                                                                 |
|------------|-------------|----------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| O(1)       | Constant    | A simple add numbers function    | For any given input, the execution will not change (number of operation remains constant)                                                                                                   |
| O(N)       | Linear      | Loop through numbers from 1 to n | Time complexity will grow in direct proportion to the size of the input data, the best practice is to try to keep our function running **below** or **within** this range of complexity     |
| O(LogN)    | Logarithmic | Find an element in sorted array  | The time complexity grows logarithmically as the input size increases; often achieved through algorithms that divide the problem size in each step, like binary search.                     |
| O($N^2$)   | Quadratic   | Nested Loops                     | The execution time is proportional to the square of the input size; common in algorithms that involve two nested loops, like bubble sort or selection sort.                                 |
| O($2^N$)   | Exponential | Double recursion in Fibonacci    | The execution time doubles with each additional element in the input size; common in algorithms with multiple recursive calls, such as calculating Fibonacci numbers using naive recursion. |
|
