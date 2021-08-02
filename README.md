# JavaScript Review 2 - Functions and Loops
This 5 challenge review covers core JavaScript concepts and is expected to take Students 1.5 hr or less

## Directions
* Create a new public GitHub repository called `javascript-concept-review-level-1`
* Clone repository and copy the contents of this README file to your README 
* Create `index.html`,`style.css`, and `main.js` files in your project
* Code your answers to each of the 5 questions using the Standard JavaScript Template described below:

> NOTE: Start with a separate JavaScript file with a function called *main()*. This should be the first function called and point of entry for execution. All other code to accomplish whatever challenge should be in it's own function called from the main() function. No JavaScript code should execute outside of a function. This pattern should be considered our 'Standard JavaScript Template' for all exercises.
```
main() {
    // call exercise1()
    // call excercise2()
    // etc.
}
```


### 1:
Write a JavaScript function that accepts a sentence of words all in lowercase, and returns every other word in all caps.  

ex. ```in a galaxy far far away``` -> ```in A galaxy FAR far AWAY```

### 2:
Write a JavaScript function that accepts a word in all lowercase or in all uppercase, and returns the word in the opposite case. Hint: see toLowercase()

ex. ```hello``` -> ```HELLO``` or ```HOWDY``` -> ```howdy```

### 3:

#### Return first n number of elemnts

Write a JavaScript function to get the first n element(s) of an array. Passing a parameter 'n' will return the first 'n' elements of the array.

ex: 
```
console.log(first([7, 9, 0, -2],3));
console.log(first([7, 9, 0, -2],1));
```
Expected Output : 
```
[7, 9, 0] 
[7] 
```
#### Return last n number of elements

Write a JavaScript function to get the last n element(s) of an array. Passing a parameter 'n' will return the last 'n' elements of the array.

ex:
```
console.log(last([7, 9, 0, -2],3)); 
console.log(last([7, 9, 0, -2],6));
```
Expected Output : 
```
[9, 0, -2] 
[7, 9, 0, -2]
```
### 4:
Write a JavaScript function to remove an element with a specific value from an array.

ex:
```
console.log(remove_array_element([2, 5, 9, 6], 5));
```
Expected Output:
```
[2, 9, 6]
```

### 5:
Create a new empty array called ```pet_list```. Add 3 pet objects to the ```pet_list``` array (each pet should have a type and a breed property) You can choose the pets.

Add a new property called ```age``` to each pet instance in ```pet_list```

Assign a number for the ```age``` for all of the pets

Iterate the list of pets and print the properties for each pet
