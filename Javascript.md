# `Javascript Interview Questions`

#### 1. What types of variables exist in Javascript? What is the difference between them?

<details>
  <summary>Answer</summary>
</details>

#### 2. Why is using var a bad practice?

`Task` What value will be assigned to the `result` variable

```js
result = 12
const result = 3
```

`Task` What value will be assigned to the `result` variable

```js
result = 12
var result = 3
```

`Task` What value will be assigned to the `result` variable

```js
result = 12
let result = 3
```

<details>
  <summary>Answer</summary>
  Task: ReferenceError + TypeError - 12 - ReferenceError
</details>

#### 3. What types of data exist in Javascript? What is the difference between them? Which data types are primitive and which are not?

<details>
  <summary>Answer</summary>
</details>

#### 4. Tell us about type conversion. How do I find out the data type?

`Task` What is the result of this expressions? Why?

```js
("b" + "a" + + "a" + "a").toLowerCase()
```

```js 
String({})
```

```js 
String({ property: null })
```

```js 
String(undefined)
```

<details>
  <summary>Answer</summary>
    Task: "banana" - [object Object] - [object Object] - "undefined"
</details>

#### 5. What is the lexical scope?

<details>
  <summary>Answer</summary>
</details>

#### 6. What conditional operators and null merge and assignment operators do you know? Why are they needed? What is an Optional Chain '?.'?

`Task` What value will be assigned to the `result` variable

```js
const value = null
const result = value || 12
```

```js
const value = null
const result = value ?? 12
```

```js
const value = 0
const result = value || 12
```

```js
const value = 0
const result = value ?? 12
```

```js
const value = ""
const result = value || "12"
```

```js
const value = ""
const result = value ?? "12"
```

<details>
  <summary>Answer</summary>
  Task: 12 - 12 | 12 - 0 | "12" - ""
</details>

#### 7. What types of functions do you know? What are arrow functions?

<details>
  <summary>Answer</summary>
</details>

#### 8. What is hoisting?

<details>
  <summary>Answer</summary>
</details>

#### 9. What is a closure ?

<details>
  <summary>Answer</summary>
</details>

#### 10. Tell us about Spread syntax

<details>
  <summary>Answer</summary>
</details>

#### 11. What is destructurization? Which entities can we destructurize?

<details>
  <summary>Answer</summary>
</details>

#### 12. How do I copy an object? How to do deep copying?

<details>
  <summary>Answer</summary>
</details>

#### 13. What is context? What are call/apply/bind for? what is their difference?

<details>
  <summary>Answer</summary>
</details>

### 14. What methods of working with an array do you know?

<details>
  <summary>Answer</summary>
</details>

### 15. What is the peculiarity of the sort and reverse methods?

<details>
  <summary>Answer</summary>
</details>

#### 16. How does inheritance work in Javascript? What is a prototype?

<details>
  <summary>Answer</summary>
</details>

#### 17. Tell us about object property descriptors and flags

<details>
  <summary>Answer</summary>
</details>

#### 18. Tell us about Javascript classes, private and protected property methods

<details>
  <summary>Answer</summary>
</details>

#### 19. What is a promise and a chain of promises? Tell us about async/await

<details>
  <summary>Answer</summary>
</details>

#### 20. What is a generator in Javascript?

<details>
  <summary>Answer</summary>
</details>

#### 21. Tell us about the loop event

`Task` In what order will the messages be displayed? Why?

```js
setTimeout(() => console.log(1), 100);

new Promise((resolve) => {
  console.log(2);
  resolve();
})
  .then(() => {
    console.log(3);
    throw new Error();
  })
  .then(() => {
    console.log(4);
  })
  .catch(() => {
    console.log(5);
  })
  .then(() => {
    console.log(6);
  });

console.log(7);

setTimeout(() => console.log(8));
```

<details>
  <summary>Answer</summary>
  Task: 2 - 7 - 3 - 5 - 6 - 8 - 1
</details>

#### 22. What is currying?

<details>
  <summary>Answer</summary>
</details>

#### 23. What are polyfills? Why are they needed?

<details>
  <summary>Answer</summary>
</details>

#### 24. What are MutationObserver? Why are they needed?

<details>
  <summary>Answer</summary>
</details>

#### 25. What are ResizeObserver? Why are they needed?

<details>
  <summary>Answer</summary>
</details>

#### 26. What is Event Bubbling in JavaScript?

<details>
  <summary>Answer</summary>
</details>

#### 27. What is the difference between localstorage, sessionStorage, cookie and IndexedDB

<details>
  <summary>Answer</summary>
</details>

#### 28. What is the difference between async and defer when loading scripts?

<details>
  <summary>Answer</summary>
</details>
