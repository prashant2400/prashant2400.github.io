---
title: Memoization application that you already have used but might not know !
excerpt: Memoization
---
### Memoization
    In the Computer Science, there is a concept of [Memoization](https://en.wikipedia.org/wiki/Memoization), where the idea is to "remember" something which is kind of expensive to compute and can later be useful, if you already knew the result, as the Wikipedia article already describes, to calculate $10!$ , you would need to multiple all the numbers from 10 to 1, which is kind of computationally expensive. If a program (process) in a later part of an execution, may need to calculate $15!$ , and it might already have saved computed result of $10!$ in a memory, it then doesn't have to calculate $15!$ all the way up to 1, but only till 11 and then we can use $10!$ result that program already knew, so in another word 

$$15!=15 \times 14 \times 13 \times 12 \times 11 \times 10!$$

and then in this process once also save values of $14$ up till $11!$ , as we are calculating that values too in process , like $n!=n*(n-1)!$

### Have we already using such technique?
    To answer this question, let us iterate briefly, how do we multiple 2 digits number. Let's call this function $M$. 
    
