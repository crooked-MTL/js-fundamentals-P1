# Fundamentals: Exercises

_We will correct these exercises in class._

## Exercise 1

```js
// Look at these expressions below and determine whether they evaluate to true or false

1. true || false (TRUE)
2. false && false (FALSE)
3. 1 < 2 && 2 > 1 (TRUE)
4. 31 < 13 || 1 < 2 && 3 > 1 (TRUE)
5. 400 <= 400 && 399 < 400 && (30 > 31 || 400 > 31) (TRUE)
6. true && false && false || false && true (FALSE)
7. true && false || true || false (TRUE)
8. true && false && false || false && true ? true && false && false || false && true : 1 < 2 && 2 > 1 (TRUE)
```

---

## Exercise 2

Given this data structure:

```js
let data = [0, [], [], [1, 2, 3, [4]]];
```

1.  How would you access the value `0`?

        ANSWER : console.log(data[0][0]);

2.  How would you access the value `3`?

        ANSWER : console.log(data[3][2]);

3.  How would you access the value `4`?

        ANSWER : console.log(data[3][3][0]);

---

## Exercise 3

- List the number of properties for each object.
- For each property, indicate its key and its value.
- For each property value, indicate its type.

```js
{ label: 'corn', price: 5.3 + '$' };

//ANSWER:
//There are 2 properties. The first properties Key is `label` & it has a string value of 'corn'
//The second properties Key is `price` and has a value of `5.3$` (5.3 being a Number and $ being a String but together creating a single String)

{ ISBN: 53532, isAvailable: true, author: 'Nakamoto' };

//ANSWER:
//There are 3 properties. The first properties Key is `ISBN` & it has a Number value of `53532`.
//The second properties Key is `isAvailable` and has a boolean value of `true`
//The third properties Key is `author` and has a string value of 'Nakamoto'
```

---

## Exercise 4

```js
// Given
let person = { name: "Bob", age: 23 };
```

What is the value of the following expressions?

1.  person.name

            ANSWER: Bob (string)

2.  person['name']

            ANSWER: Bob (string)

3.  person[name]

            ANSWER: undefined
