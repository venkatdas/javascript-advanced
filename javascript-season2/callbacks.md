### Callbacks

- Callback is a function that we can pass as an argument to other function
  #### Why do you need callbback functions
JavaScript runs code sequentially in top-down order.
However, there are some cases that code runs (or must run) after something else happens and also not sequentially. 
This is called asynchronous programming

![image](https://github.com/venkatdas/javascript-advanced/assets/43024084/14a8276a-5318-4453-aefd-cf310e7dc638)

- Due to callbacks we are facing two disadvantages

1) Callback hell or Pyramid of doom
2) inversion of control

- Callback Hell is a situation in JavaScript where multiple nested callback functions make your code look like it’s been through a blender on the highest setting.
![image](https://github.com/venkatdas/javascript-advanced/assets/43024084/3211ffa6-db0c-4775-91a0-383a8ba537ce)

- "Inversion of Control" (IoC) in the context of callbacks refers to the loss of control over the execution flow of your program. When you pass a callback to another function (often a library or a framework), you are essentially handing over control of when or if your callback will be called, how many times it will be called, and with what arguments.
