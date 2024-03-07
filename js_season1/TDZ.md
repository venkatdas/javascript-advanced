#### Temporal Dead Zone


- TDZ stands for “Temporal Dead Zone” in JavaScript. It refers to the period of time in which a variable exists but cannot be accessed or referenced before it is declared with the let or const keywords.

  
- In JavaScript, variables declared with let and const are hoisted to the top of their respective scopes, but they are not initialized immediately. Instead, they enter the TDZ until their declarations are reached during the execution of the code.

- During the TDZ, if you try to access or reference a variable, a ReferenceError will be thrown. This is because the variable exists in the scope but has not been assigned any value yet.

- Example

  ![image](https://github.com/venkatdas/javascript-advanced/assets/43024084/c1453deb-8c31-4bac-87da-333222f43a65)

- In this example, trying to access myVariable before its declaration will result in a ReferenceError due to the TDZ. Once the variable is declared, it can be accessed normally.

_____________________________________


![image](https://github.com/venkatdas/javascript-advanced/assets/43024084/4a9dee8f-4ae5-4dfd-866a-44bf6ce836ac)


- let and const are hoisted , but they are temporal dead zone due to that we can not access the variables.
- From above they are hoisted in separate space .. It is the time of our debugger line go to next executed line until that they are in temporal dead zone.
