# AMA - 16/03/2026

### Q1. What is a Promise?

**Ans:** A Promise in JavaScript is an object that represents the result of an asynchronous operation. It has three states: **Pending, Fulfilled, and Rejected**.

---

### Q2. What is a Callback Function?

**Ans:** A callback function is a function that is passed as an argument to another function and executed after the main function completes.

---

### Q3. What is a Higher Order Function?

**Ans:** A Higher Order Function is a function that takes another function as an argument or returns a function. Examples include **map(), filter(), and reduce()**.

---

### Q4. How do you export a file in JavaScript?

**Ans:** Export is used to share functions, variables, or objects between files using **export** and **import**.

Example:

```javascript
export const name = "Akshat";
```

---

### Q5. What is the difference between let and const?

**Ans:**

* **let** allows reassignment but cannot be redeclared in the same scope.
* **const** cannot be reassigned or redeclared after declaration.

---

### Q6. What is the difference between `=`, `==`, and `===`?

**Ans:**

* `=` is an **assignment operator**.
* `==` compares **values only**.
* `===` compares **both value and data type**.

---

### Q7. What are variables in JavaScript?

**Ans:** Variables are used to store data values. They can be declared using **var, let, or const**.

---

### Q8. What is Hoisting?

**Ans:** Hoisting is JavaScript's behavior of moving **variable and function declarations to the top of their scope before execution**.

---

### Q9. Define Data Types in JavaScript.

**Ans:** JavaScript has two types of data types:

**Primitive Types**

* String
* Number
* Boolean
* Null
* Undefined
* Symbol
* BigInt

**Non-Primitive Types**

* Object
* Array
* Function

---

### Q10. What are the phases of the Global Execution Context?

**Ans:** The global execution context has two phases:

1. **Memory Creation Phase** – Variables are assigned `undefined` and functions are stored in memory.
2. **Execution Phase** – Code is executed line by line and values are assigned.

---

### Q11. What is Scope?

**Ans:** Scope determines where variables can be accessed in a program. Types include **Global Scope, Function Scope, and Block Scope**.

---

### Q12. Explain the filter() function.

**Ans:** `filter()` creates a new array containing elements that satisfy a given condition.

Example:

```javascript
let numbers = [10,20,30,40];
let result = numbers.filter(num => num > 20);
```

---

### Q13. Explain the map() function.

**Ans:** `map()` creates a new array by applying a function to each element of the original array.

Example:

```javascript
let numbers = [1,2,3];
let result = numbers.map(num => num * 2);
```

---

### Q14. What are the different ways to declare a function in JavaScript?

**Ans:** Functions can be declared in three main ways:

1. **Function Declaration**

```javascript
function greet(){
  console.log("Hello");
}
```

2. **Function Expression**

```javascript
const greet = function(){
  console.log("Hello");
}
```

3. **Arrow Function**

```javascript
const greet = () => {
  console.log("Hello");
}
```

---

### Q15. What happens when there is no return in a function?

**Ans:** If a function does not return any value, JavaScript automatically returns **undefined**.

---

### Q16. Explain the `this` keyword.

**Ans:** The `this` keyword refers to the **object that is calling the function**.
