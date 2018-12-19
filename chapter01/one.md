# Chapter 1

### Section One

> This is a block quote. And so on .

* This is not 
  * a block
  * quote
* And
  * so on
  * and on.
  
## 0. Collapsible markdown?

<details><summary>CLICK ME</summary>
<p>

#### yes, even hidden code blocks!

```python
print("hello world!")
```

</p>
</details>



## 0. Collapsible markdown?

<details><summary>CLICK ME AGAIN</summary>
<p>

#### yes, even hidden code blocks!

```python
print("hello world!")
```

</p>
</details>


## 1. How do you create a collapsible markdown section?
<details><summary>Click me</summary>
<p>
The entire section is describe by a _details_ tag, followed
by a clickable element within a _summary tag_, and lastly ending in a _paragraph_
tag. ie:

  &lt;details>&lt;summary>click me&lt;/summary>
    &lt;p>
      content
    &lt;/p>
  &lt;/details>

You can also include code blocks using triple back ticks ```

 ```javascript
let theNumber = Number(prompt("Pick a number"));
if (!Number.isNaN(theNumber)) {
  console.log("Your number is the square root of " +
              theNumber * theNumber);
}
```

</p>
</details>


## 2. What are side effects? 

<details><summary>CLICK ME</summary>
<p>
If a javascript statement changes the world in some way, those changes are called side effects.

It could display something on the screen—that counts as changing the world—or it could change the internal state of the machine in a way that will affect the statements that come after it.
Statements that only return values and don't otherwise change the world are said to have no side effects.
</p>
</details>

## 3. Functions that don't have an explicit return statement return...?

<details><summary>CLICK ME</summary>
<p>

undefined
</p>
</details>

## 4. Bindings declared with *let* or *constant* are local in scope to the _____ which defined them?

<details><summary>CLICK ME</summary>
<p>

block
</p>
</details>

## 5. What is lexical scope?

<details><summary>CLICK ME</summary>
<p>
The set of bindings visible inside a block is determined by the place of that block in the program text. Each local scope can also see all the local scopes that contain it, and all scopes can see the global scope. This approach to binding visibility is called lexical scoping.
</p>
</details>

## 6. What's the difference between a function definition and a function declaration?

<details><summary>CLICK ME</summary>
<p>
A function definition is a regular binding where the value of the binding is a function.

```javascript
const square = function(x) {
  return x * x;
};
```
A function declaration defines the binding and points it at the funcition.

```javascript
function square(x) {
  return x * x;
}
```
Declarations allow for HOISTING. 

That's because Function declarations are not part of the regular top-to-bottom flow of control. They are conceptually moved to the top of their scope and can be used by all the code in that scope. This is sometimes useful because it offers the freedom to order code in a way that seems meaningful, without worrying about having to define all functions before they are used.
</p>
</details>

## 7. Do arrow functions require a return statement?

<details><summary>CLICK ME</summary>
<p>

No.

```javascript
const square1 = (x) => { return x * x; };
const square2 = x => x * x;

When an arrow function has no parameters at all, its parameter list is just an empty set of parentheses.

const horn = () => {
  console.log("Toot");
};
```

</p>
</details>


## 8. What is the call stack? 

<details><summary>CLICK ME</summary>
<p>
The javascript engine keeps track of the context from which each function is called.
It does this to manage control flows through functions.

The place where the computer stores this context information is the **call stack**.

 Every time a function is called, the current context is stored on top of this stack. When a function returns, it removes the top context from the stack and uses that context to continue execution.

</p>
</details>


## 9. What's closure? 

<details><summary>CLICK ME</summary>
<p>

Closures are data structures with both a code and a data component. 

Conceptually, a closure consists of an open lambda term, plus an environment dictating the values of its free variables.

So, being able to reference a specific instance of a local binding in an enclosing scope—is called closure. 

A function that references bindings from local scopes around it is called **a closure**. This behavior not only frees you from having to worry about lifetimes of bindings but also makes it possible to use function values in some creative ways.

```javascript
function multiplier(factor) {
  return number => number * factor;
}

let twice = multiplier(2);   // twice closes over the argument '2' passed into the multiplier function
console.log(twice(5)); 
// → 10
```
</p>
</details>


## 

<details><summary>CLICK ME</summary>
<p>


</p>
</details>


## 

<details><summary>CLICK ME</summary>
<p>


</p>
</details>


## 

<details><summary>CLICK ME</summary>
<p>


</p>
</details>


## 

<details><summary>CLICK ME</summary>
<p>


</p>
</details>






<!---
Collapsible Template:
-->

## 

<details><summary>CLICK ME</summary>
<p>


</p>
</details>


## 

<details><summary>CLICK ME</summary>
<p>


</p>
</details>


