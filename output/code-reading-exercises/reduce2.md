# reduce2


`function e(f,g,h){return f.filter(x=>g(x)&&h(x));}`

```
⬇️
⬇️
⬇️
⬇️
⬇️
⬇️
⬇️
⬇️
⬇️
⬇️
⬇️
⬇️
⬇️
⬇️
⬇️
⬇️
⬇️
⬇️
⬇️
```

This function takes three parameters:

- f is an array
- g is a function that takes one parameter and returns a boolean
- h is also a function that takes one parameter and returns a boolean

The function will filter the elements of the array f and returns a new array that contains only the elements that passed the test of both function g and function h.

```
⬇️
⬇️
⬇️
⬇️
⬇️
⬇️
⬇️
⬇️
⬇️
⬇️
⬇️
⬇️
⬇️
⬇️
⬇️
⬇️
⬇️
⬇️
⬇️
```

This function could be useful in a real-world application where you need to filter an array of data based on multiple conditions. For example, you have an array of products and you want to filter out all the products that are out of stock and also those that are overpriced, you could use this function to filter the products based on two separate functions that check the stock and the price of the products and return a boolean value.
Another example could be filtering an array of employees based on their job title and their salary, you could use this function to filter the employees based on two separate functions that check the title and the salary of the employees and return a boolean value.
It also can be used in any application that handles a large amount of data and need to filter it based on multiple conditions.
