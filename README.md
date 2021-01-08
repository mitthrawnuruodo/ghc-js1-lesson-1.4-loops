# Exercises for Programming Foundations Lesson 4

## Exercise 1
a) Make a `for` loop counting from 0 through 10 (including the 10). Console log out the numbers.

b) Make a `for` loop counting from 6 throughto 11 (including the 11). Console log out the numbers.

c) Make a `for` loop counting from 10 through 1 (including the 1). Console log out the numbers.

## Exercise 2
a) Make a `while` loop counting from 0 through 10 (including the 10). Console log out the numbers.

b) Make a `while` loop counting from 6 throughto 11 (including the 11). Console log out the numbers.

c) Make a `while` loop counting from 10 through 1 (including the 1). Console log out the numbers.

## Exercise 3
a) Make a `for` loop counting from 1 through 10. Console log out the numbers, except for 5 (let the loop skip over 5).
> Tip look at `continue`

b) Make a while loop counting down from 10 through 0, but stops after 2 is reached. Console log out the numbers (10-2).
> Tip look at `break`

## Exercise 4
a) Make a do...while loop counting down from 10 through 5. Console log out the numbers.

b) What becomes the output if you set the counter to 0 before the loop?

## Exercise 5
Make a `for` loop that counts just the even numbers (0, 2, 4, 6, ...) from 0 through 20. Console log out the numbers.
> Tip adjust the iteration in the final expression.

## Exercise 6
Given an array: 

```js
const catBreeds = ["Abyssinian", "Balinese", "Birman", "Chartreux", "Egyptian Mau", "Maine Coon", "Norwegian Forest Cat", "Ragdoll", "Siamese", "Siberian"];
```

Use a `for...of` loop and console log out the diffent cats with the same lead text for each breed.

## Exercise 7 - Level 2
Using a double loop, make the following pattern: 
```
*
**
***
****
*****
```

## Excercize 8 - Level 2

Fizz buzz is a group word game for children to teach them about division. Players take turns to count incrementally, replacing any number divisible by three with the word "fizz", and any number divisible by five with the word "buzz".

Players generally sit in a circle. The player designated to go first says the number "1", and the players then count upwards in turn. However, any number divisible by three is replaced by the word fizz and any number divisible by five by the word buzz. Numbers divisible by 15 become fizz buzz.

a) Using a `for` loop, make a variant of Fizz buzz where you count from 1 through 20 and add each number to a text string as you count. In the end console log out the answer string.

> The final answer should look like this: "1, 2, Fizz, 4, Buzz, Fizz, 7, 8, Fizz, Buzz, 11, Fizz, 13, 14, Fizz Buzz, 16, 17, Fizz, 19, Buzz"

b) Make a variant where you count from 1 through 30, and buzz is used for numbers divisible by 7 (not 5).