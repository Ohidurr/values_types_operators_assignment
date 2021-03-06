# Values, Types & Operators Exercises

1. What are the types of the following expressions and what do they evaluate to, and why?
* `17       //number, evaluates to 17
* `1 + 2 * 3 + 4` // number, evaluates to 11
* `800 / 80 / 8` // number, evaluates to 1.25
* `400 > 200` // boolean, true b/c 400 is greater than 200
* `1 !== 1`// boolean, true
* `true || false` // boolean, true, b/c the boolean can be one of the two expressions.
* `true && false` // boolean, false, b/c it requires both statements to be true
* `20 % 6` //module, 2, 20/6 = 3 Remainder 2.
* `'a' + 'b'`// string, ab b/c it is combining two characters, a + b = ab

2. What will the following return?
* `typeof 4` // number
*  `typeof 'hello'` // string
*  `typeof true` // boolean
* `2 === 1 || 3 === 4` // false, b/c the code will stop at || and 2 does not === 1

3. Create a truth table for the expression A || B.
```js
|   A   |   B   | A || B |
| true  | true  | true  |
| false | true  | true  |
| true  | false | true  |
| false | false | false |
```
For reference, here is a truth table for the expression A && B:

``` js

|   A   |   B   | A !! B |
| true  | true  | true  |
| false | true  | false |
| true  | false | false |
| false | false | false |


```
4. Create a truth table for the expression !A && !B.
``` js
|   A   |   B   | !A && !B |
| true  | true  | false  |
| false | true  | false |
| true  | false | false |
| false | false | true |
```
For reference, here is a truth table for the expression A && !B:

``` js

|   A   |   B   |   !B   | A && B |
| true  | true  | false  | false |
| false | true  | false  | false |
| true  | false | true   | true  |
| false | false |  true  | false |

```
5. Create a truth table for the expression !(A || B).
```js
|   A   |   B   | !(A || B) |
| true  | true  | false  | 
| false | true  | false  |
| true  | false | false  |
| false | false | true   |
```
6. Write a step-by-step evaluation for the following expression (remember order of operations): `2 + 3 * 2 + 1`.
``` js
  2 + 3 * 2 + 1
  2 + 6 + 1
  8 + 1
  9
```
  For reference, here is a exp of a step-by-step evaluation:

  ```js
  1 + 2 + 3 + 4  
      3 + 3 + 4
          6 + 4
              10
  ```


 7. Write a step-by-step evaluation for the following expression (remember order of operations): `4 / 2 + 8 / 4`.
``` js
  4 / 2 + 8 / 4
  2 + 8 / 4
  2 + 4
  6
```

 8. Write a step-by-step evaluation for the following expression: `'ca' + 'ter' + 'pi' + 'llar'`.
``` js
  cater + pi + llar
  caterpi +llar
  caterpillar
 ```
 9. Write a step-by-step evaluation for the following expression: `2 * 4 === 8 && 'car' + 'pool' === 'carpool'`.
 ``` js
 2 * 4  === 8 && 'car' + 'pool' === 'carpool'
 8 === 8 && 'carpool' === 'carpool'
 true
```
10. Write a step-by-step evaluation for the following expression: '1' + '2' + '3' - '1'.
```js
1 + 2 + 3 - 1
3 + 3 - 1
6 - 1 
5
```

