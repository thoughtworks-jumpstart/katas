# Algorithm and Data Structures

## Beginner level

### Weighted random choices

Let’s say you’re making a word game that generates a random letter from the alphabet. However, we do not want the letters to have an equal probability. See [letter frequency on Wikipedia](https://en.wikipedia.org/wiki/Letter_frequency).

```
const letters = ['a','b','c','d','e','f','g','h', 'i','j','k','l','m','n','o','p','q','r','s', 't','u','v','w','x','y','z'];
```

How do we represent each probability in an uneven distribution of letters in the English language? We do this by “weighting” each value. Let's store these weights in their own array:

```
var weights = [9, 2, 2, 4, 12, 2, 3, 2,
9, 1, 1, 4, 2, 6, 8, 2, 1, 6, 4,
6, 4, 2, 2, 1, 2, 1];
```

How can we generate a random letter based on weights?

1. First solution http://prosepoetrycode.potterpcs.net/2015/05/weighted-random-choices-js/
2. Second solution http://www.javascriptkit.com/javatutors/weighrandom2.shtml

What are the pros and cons of the solutions?

### Others

- [Sum of all positive numbers in an array](https://www.codewars.com/kata/sum-of-positive/javascript)
- [Sum without highest and lowest number](https://www.codewars.com/kata/sum-without-highest-and-lowest-number/javascript)
- [Find the smallest integer in the array](https://www.codewars.com/kata/find-the-smallest-integer-in-the-array/javascript)
- [Maximum product of adjacent numbers](https://www.codewars.com/kata/maximum-product/javascript)
- [Filtering out strings in an array](https://www.codewars.com/kata/list-filtering/javascript)
- [Abbreviate a Two Word Name](https://www.codewars.com/kata/abbreviate-a-two-word-name/javascript)
- [Fizz Buzz](https://leetcode.com/problems/fizz-buzz/)
- [Fizz Buzz in too much detail](https://www.tomdalling.com/blog/software-design/fizzbuzz-in-too-much-detail/)

## Other lists of katas

- [Fun Javascript Practice on Codewars](https://www.codewars.com/collections/fun-javascript-practice)
- [Beginner level katas on Codewars](https://www.codewars.com/collections/beginners)
