# JS Destruction Lab
## Instructions
1. Consider the following array:
````
const colors = ["white", "blue", "yellow", "black", "red", "green"];
````
Using array destructuring assign the first 2 elements to `firstColor` and `secondColor` variables and assign the remaining elements to `otherColors` variable. Display the values of these 3 variables.
````
console.log(firstColor); //white
console.log(secondColor); //blue
console.log(otherColors); //["yellow", "black", "red", "green"]
````

2. Write a function called `displayName()` that takes an object as an argument and prints the person's first and last name. Use object destructuring in the function argument. And also, use template strings when printing the first and last name.
````
displayName(person); //Mark Beasley
````

3. Create a function named `goToSecondClass()` that accepts a destructured object as a parameter. The parameter extracts the `"secondHour"` property of the object. The function should return this statement:
````
"Time to go to {property_value} class!"
````
Example: `"Time to go to Programming class!"`

You can test your function with this object:
````
const myClasses = {
  firstHour: "Ethics",
  secondHour: "Programming",
  thirdHour: "Biology"
};
````

4. Write a function called `calculateSalesTotals()` which accepts an array as an argument and returns an array with new two new keys (`sale` and `total`). The key 'sale' equals the calculated sale price based on the original price and the discount. The key 'total' equals the computed total based on stock, the original price and the discount. You have to use Object Destructuring on the objects in the sales array and Object Default Values for the discount key. The default value would be 0.0.
