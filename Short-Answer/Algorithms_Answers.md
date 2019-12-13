#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I

a)
I think this would be O(n). If n is 5 for example, the loop runs
while 'a' (which is 0 initially) < 125. On the first pass 'a' becomes 25.
On the second, 'a' becomes 50, etc etc. Increasing by 25 each pass will take 5
passes to reach 125 and break out of the loop, in other words, it will take n passes.


b)
I think this would be O(n * log(n)) since the outer loop is going to run n time regardless
of what happens in the inner loop, we first get n.
Then under the condition of the inner loop, the number (which is j) that has to reach the value of n before the
loops breaks is growing in a manner like: (1, 2, 4, 8, 16, 32, etc) 
so that as the input size of n gets larger, j will catch up to n more quickly relative to the size of that number (n).

So I figure the first loop is n, and the inner one is log(n), so I multiply the to get n * log(n).


c)
I think this would be O(n). Seems like the recursion will run as many times as the input number 'bunnies'.
The reason being that the base case is 0, and 'bunnies' is only reduced by 1 every recursion. So whatever
'bunnies' happens to be, it will take that many calls to get to the base case and start returning values
up the call stack.

## Exercise II


