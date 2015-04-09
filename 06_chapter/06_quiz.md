**WDI Fundamentals Unit 6**

Read the following code and then answer the questions below.

```js
var monkees = [ 'Peter Tork', 'Micky Dolenz', 'Davy Jones', 'Michael Nesmith'];
```

---

What would `monkees.length` evaluate to?

- [x] 4
- [ ] 3
- [ ] 1

> Not quite.
> There are four string elements within the monkees array, so monkees.length
> would equal 4

---

Read the following code and then answer the questions below.

```js
var rainbowColors = ['red', 'orange', 'yellow', 'green', 'blue', 'indigo', 'violet'];
for (var i = 0; i < rainbowColors.length; i++) {
  console.log(rainbowColors[i]);
}
```
---

What does the above for loop do when executed?

- [x] It prints each item in the array "rainbowColors" to the console
- [ ] It reverses the order of the elements in the array "rainbowColors"
- [ ] It prints the index value of each element in the array "rainbowColors"
- [ ] It returns a new array filled with the same elements from the "rainbowColors" array

> Not quite.
> The for loop iterates through each element in the rainbowColors array, printing each element in the console.
---

Read the following code and then answer the questions below.

```js
var num = [2, 13, 17];
function myFunction(num) {
  return num.map(function timesTwo(x) { return x * 2 });
}
```
---

What does myFunction do?

- [ ] Reverses the array
- [x] Returns a new array with numbers twice as large as the original
- [ ] Initializes a new Google map and uses the array as coordinates
- [ ] This is invalid JavaScript code

> Not quite.
> myFunction takes the existing array numbers, and executes the timesTwo function
> on each element, resulting in a new array with the values [4, 26, 14].

---

[Here's an exercise to practice what we've just gone over.](07_exercise.md)