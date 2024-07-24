# JavaScript Notes

## Advanced array methods

### forEach() loops through every single elemnt in an array
    - take a call back function as argument
    - does not return a new array
    - does not require a return statement

- Each advanced array method we are working with have a callback function
    - This function takes up to 3 arguments only first is required
    - 1. Current Value, current element being processed in the array
    - 2. index index of the current element being processed in the array
    - 3. This is the array on which the map method was called on
    - filter cb function take an element of an array, and returns a boolean value
    - if returns true, element will be included in new filtered array
    - if false will be excluded
    - map cb function takes in an element of an array as an argument
    - returns a transformed version of the element
    - returned values of cb will be used to create a new array
    - find method cb function takes in element of an array
    - returns a boolean value either true or false, if element returns true
    - then element will be returned by the .find method
    - if all elements return false, returns undefined

### filter() method
    - returns a new array with elements that return true to the boolean


### map() method
    - mainly used for transforming elements from on array
    - to some other type in a new array
    - requires a return statement automatically returns a new array


### find() method
    - similar to filter returns statement that is true
    = does not return array returns a single element
