# Code Challenge: High-Order Array Methods

## Instructions

1. Clone down this assignment to AWS Cloud9. 
2. Code your solution using JavaScript in `index.js`. 
3. **Be sure to run and test your code throughly!**
4. By the end of Code Challenge, **commit and push your changes up to Github**.
5. Using the browser, verify that your solution is in your remote repo on Github.

## Problems 
### **Test all your solutions for the questions 1-4 with the following variable:** 

```jsx
const alumni = [
{name:'Jarrit', job:'TPT',language:'JavaScript', age:23}, 
{name:'Stephanie', job:'JPMorgan',language:'JavaScript', age:24}, 
{name:'Devonte', job:'WW',language:'JavaScript', age:23}, 
{name:'Enmanuel', job:'Asana',language:'JavaScript', age:23},
{name:'Shemar', job:'SquareSpace',language:'JavaScript', age:23},
{name:'Cielo', job:'NYT',language:'JavaScript', age:22},
{name:'Carmen', job:'Marcy Lab School',language:'JavaScript', age:21},
{name:'Itzel', job:'Marcy Lab School',language:'JavaScript', age:22},
{name:'Ray', job:'Square Space',language:'JavaScript', age:21},
{name:'Jan', job:'Square Space',language:'JavaScript', age:22},
{name:'Uzma', job:'Thyme Care',language:'JavaScript', age:22}]
```

**Solve the following problems using higher order methods**

1. Write a function named `oddJob` that takes an array of objects and returns an array of objects if the job length is an odd number. 
    
    ```jsx
    oddJob(alumni) //returns [
      { name: 'Jarrit', job: 'TPT', language: 'JavaScript', age: 22 },
      { name: 'Enmanuel', job: 'Asana', language: 'JavaScript', age: 21 },
      {
        name: 'Shemar',
        job: 'SquareSpace',
        language: 'JavaScript',
        age: 23
      },
      { name: 'Cielo', job: 'NYT', language: 'JavaScript', age: 21 },
      { name:'Uzma', job:'Thyme Care',language:'JavaScript', age:22 }
    ]
    ```

2. Write a function named `ninetiesBabies` that takes an array of objects and returns an array of only the objects where the age property is larger than 21.
    
    ```jsx
    ninetiesBabies(alumni) // returns [
      { name: 'Jarrit', job: 'TPT', language: 'JavaScript', age: 22 },
      { name: 'Devonte', job: 'WW', language: 'JavaScript', age: 23 },
      { name: 'Shemar', job: 'SquareSpace', language: 'JavaScript', age: 23 }
    ]
    ```

3. Write a function named `updateLanguage` that takes an array of objects and updates the language value to ES6 if the language is JavaScript, return the entire object. 
    
    ```jsx
    updateLanguage(alumni) // [
      { name: 'Jarrit', job: 'TPT', language: 'ES6', age: 22 },
      { name: 'Stephanie', job: 'JPMorgan', language: 'ES6', age: 21 },
      { name: 'Devonte', job: 'WW', language: 'ES6', age: 23 },
      { name: 'Enmanuel', job: 'Asana', language: 'ES6', age: 21 },
      { name: 'Shemar', job: 'SquareSpace', language: 'ES6', age: 23 },
      { name: 'Cielo', job: 'NYT', language: 'ES6', age: 21 }
    ]
    ```


