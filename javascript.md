## Javascript

#### Data types:
1. **Number** - for numbers of any kind: integer or floating-point, integers are limited by ±(253-1).  
 Also Infinity, -Infinity and NaN.
2. **Bigint** - for integer numbers of arbitrary length. More then (253-1). 
3. **String** - string for strings. A string may have zero or more characters, there’s no separate single-character type.
4. **Boolean** - for true/false logical type.
5. **Null** - for unknown values – a standalone type that has a single value null. Empty value. 
6. **Undefined** - for unassigned values – a standalone type that has a single value undefined. Value is not assigned. 
7. **Symbol** - for unique identifiers.
8. **Object** - complex data structures.

To define data type `typeof x`, but `typeof null -> object`, it's language mistake. 

#### Javascript features:
* **dynamic typesation** - allow to redefine variable and change it type. Variable connected to the value by assigning, but by defining. 
* **weak typing** - in case of type conversion.
* **automation memory management** - controlled by garbage collector. Variables and objects are deleted when they aren't reachable. 
* **prototype programming** - Thus inheritance in JavaScript is covered by a delegation automatism that is bound to the prototype property of constructor functions.
* **functions is a first-class citizen** - functions could be used as variables and could be passed and returned on another functions. 

#### Closures
A closure is the combination of a function bundled together (enclosed) with references to its surrounding state (the lexical environment). In other words, a closure gives you access to an outer function's scope from an inner function. In JavaScript, closures are created every time a function is created, at function creation time.  
After variable request, function check it inside, then go to outer scope through lexical environment, until it reaches global scope. 

#### Event loop, micro and macro tasks:
**Event loop** - endless loop of js browser engine, execute tasks in queue order, put older task in stack, after this engine waiting for new tasks. 
**Macro tasks** - scripts, Timeout, mousemove.  
**Micro tasks** - microtasks come solely from our code. They are usually created by promises: an execution of **.then/catch/finally**
Micro tasks event loop embedded in macro tasks loop, after every macro task executes all micro tasks from it own loop. 
```javascript
setTimeout(() => alert("timeout"));

Promise.resolve()
  .then(() => alert("promise"));

alert("code");
// code
// promise
// timeout
```

<img src="https://github.com/akashuba/frontend_checklist/blob/main/img/event-loop.png" alt="drawing" width="400"/>.   
Image from [javascript.info](https://javascript.info/event-loop#event-loop).  
[MDN - event loop](https://developer.mozilla.org/en-US/docs/Web/JavaScript/EventLoop)
