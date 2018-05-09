Random Quote Generator
===

This project was bootstrapped with [Create React App].

This is simple Random Quote Generator from [freeCodeCamp.org] projects - refactored so it uses ReactJS.

Solution used here is quite simple - I am providing fixed arrays of quotes and color values. After clicking _**New Quote**_ button app uses 
```js
Math.floor(Math.random() * array.length);
``` 
to randomly select index of quote and color value in those arrays. Then it smoothly transfers from old values to new ones. Transitions are defined inside CSS.

<!-- My Referrences -->
[Create React App]: https://github.com/facebookincubator/create-react-app
[freeCodeCamp.org]: https://www.freecodecamp.org/
