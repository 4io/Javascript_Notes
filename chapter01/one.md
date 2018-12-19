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

## 

<details><summary>CLICK ME</summary>
<p>


</p>
</details>








Collapsible Template:

## 

<details><summary>CLICK ME</summary>
<p>


</p>
</details>


