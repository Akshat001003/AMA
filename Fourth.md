# AMA Session Report - 24/03/2026

---

## Q1. What is position: absolute in CSS?

**Ans:**
`position: absolute` is used to position an element relative to its nearest positioned ancestor (i.e., an ancestor with position other than static). If no such ancestor exists, it is positioned relative to the document body.

---

## Q2. What are shift() and unshift() in JavaScript?

**Ans:**

* `shift()` removes the first element from an array.
* `unshift()` adds one or more elements to the beginning of an array.

**Example:**

```js
let arr = [1,2,3];
arr.shift();     // [2,3]
arr.unshift(0);  // [0,2,3]
```

---

## Q3. What are some common errors in JavaScript?

**Ans:**
Common JavaScript errors include:

* Syntax Errors (missing brackets, commas)
* Reference Errors (using undefined variables)
* Type Errors (wrong data type usage)
* Logical Errors (incorrect logic in code)

---

## Q4. Is JavaScript statically or dynamically typed?

**Ans:**
JavaScript is a **dynamically typed** language, meaning variable types are determined at runtime and can change.

---

## Q5. What is the difference between [] == [] and [] === []?

**Ans:**
Both return `false` because arrays are reference types:

* `[] == []` → false
* `[] === []` → false

Each array has a different memory reference.

---

## Q6. What is Callback Hell?

**Ans:**
Callback Hell refers to deeply nested callback functions, making code hard to read and maintain.

**Example:**

```js
doSomething(function(){
  doSomethingElse(function(){
    doAnotherThing(function(){
      // nested callbacks
    });
  });
});
```

---

## Q7. How to overcome Callback Hell?

**Ans:**
Ways to overcome Callback Hell:

* Use Promises
* Use async/await
* Modularize code into smaller functions

---

## Q8. What is Logical AND (&&) and Logical OR (||)?

**Ans:**

* `&&` (AND): Returns true if both conditions are true
* `||` (OR): Returns true if at least one condition is true

**Example:**

```js
true && false // false
true || false // true
```

---

## Q9. What is Hoisting?

**Ans:**
Hoisting is JavaScript's default behavior of moving declarations to the top of the scope before execution.

---

## Q10. What is the type of NaN?

**Ans:**
`typeof NaN` returns `"number"` even though it means "Not a Number".

---

## Q11. How to access HTML elements in JavaScript?

**Ans:**
You can access elements using:

* `document.getElementById()`
* `document.getElementsByClassName()`
* `document.querySelector()`
* `document.querySelectorAll()`

---

## Q12. What is CSS Tree Structure?

**Ans:**
CSS follows a hierarchical structure similar to a tree, where elements are nested inside each other (parent-child relationship). Styles cascade from parent to child unless overridden.

---

## Q13. Will Promises make JavaScript synchronous or asynchronous?

**Ans:**
Promises **do not make JavaScript synchronous**. They help manage asynchronous operations more efficiently and cleanly.

---

## Q14. Name some mutable methods in JavaScript.

**Ans:**
Mutable methods modify the original array:

* `push()`
* `pop()`
* `shift()`
* `unshift()`
* `splice()`
* `sort()`

---

## Q15. What is synchronous and asynchronous JavaScript?

**Ans:**

* **Synchronous:** Code executes line by line
* **Asynchronous:** Code executes without blocking, allowing other operations to run

---

## Q16. How to convert synchronous code to asynchronous?

**Ans:**
You can convert sync code to async using:

* `setTimeout()`
* Promises
* `async/await`

**Example:**

```js
async function fetchData() {
  let data = await fetch("https://api.example.com");
  console.log(data);
}
```

---

