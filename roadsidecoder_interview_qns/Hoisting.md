## Hoisting
- By Hoisting it means the behavior of moving the variables or function declarations to the top.



![image](https://github.com/venkatdas/javascript-advanced/assets/43024084/219286fe-d611-48f8-b3ad-d31d425986c8)

- We are accessing the varaiable before intialization and it leads to undefined

 - const and let hoisted in temporal deadzone
 - 
```Javascript
console.log(myLetVar); // ReferenceError: Cannot access 'myLetVar' before initialization
let myLetVar = 3;

```


#### Function expression hoisting

```javascript
myFunc(); // TypeError: myFunc is not a function

var myFunc = function() {
    console.log("Hello from function expression!");
};
```

- The variable myFunc is hoisted, but its assignment as a function happens at runtime. Hence, trying to call it before the assignment results in a TypeError.


## Javascript execution context
![Uploading image.png…]()

