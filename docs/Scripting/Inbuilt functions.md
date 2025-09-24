The functions onReady and update are the core components of a JSGameObejct script.

**onReady** is called everytime the script is first loaded, eg. when the application starts.
**not on hot reloads**

**update** is called every frame and meant to progress in the game logic.

All functions and variables outside of these functions will be "executed" every time the script loads, meaning definitions will "reset" the value of a varible, thus it is recommend it to declare but not initialise variables in global scope, variable definitions that are not supposed to be reloaded every time should be contained in the **onReady** function.

## Math functions


```js
sin();//sine
cos();//cosine
abs();//absolute value
```

