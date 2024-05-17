### Student ID: 11205670

## Explanation of Task 1
Task 1 consists of a function named `processArray` which will:

Accept an array of numbers as its parameter.
Process this array and return a new array where:
Each even number is squared (multiplied by itself).
Each odd number is tripled (multiplied by three).


## Explanation of Task 2
Task 2 consists of a  function named `formatArrayStrings` which will:

Accept two arrays:
The first array contains strings.
The second array contains numbers that have been processed by another function in Task 1 called `processArray`.
Modify each string in the first array based on the corresponding number in the second array:
If the number is even, the string will be converted to uppercase.
If the number is odd, the string will be converted to lowercase.
The function will then return the modified array of strings.


## Explanation of Task 3
In task 3, we are to create a JavaScript file named `userInfo.js` and write a function called `createUserProfiles` which:

Take two inputs:
An array of original names.
An array of modified names, which comes from the output of the `formatArrayStrings` function you created in Task 2.
Generate an array of objects. Each object will represent a user profile and should contain:
`originalName`: The name from the array of original names.
`modifiedName`: The corresponding name from the array of modified names.
`id`: A unique identifier for each user profile, starting at 1 and increasing by 1 for each subsequent profile.
