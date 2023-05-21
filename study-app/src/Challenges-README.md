JAVASCRIPT

Challenge:

Write a JavaScript program that demonstrates the use of objects and classes. Define a class called "Person" with properties for name and age, as well as a method called introduce that outputs a personalized introduction. Create two instances of the "Person" class and call the introduce method on each instance.

Expected Output:

The expected output of the program should be:

My name is John Doe and I am 25 years old.
My name is Jane Smith and I am 30 years old.


Challenge 1:

Write a JavaScript program that utilizes the .map method to transform an array of numbers. Create an array of numbers and use .map to square each number in the array. Finally, print the transformed array.

Expected Output:

The expected output of the program should be the transformed array of squared numbers.


Challenge 1:

Write a JavaScript program that utilizes the .map method to transform an array of numbers. Create an array of numbers and use .map to square each number in the array. Finally, print the transformed array.

Expected Output:

The expected output of the program should be the transformed array of squared numbers.

Example:

javascript
Copy code
const numbers = [1, 2, 3, 4, 5];

const squaredNumbers = numbers.map((number) => number ** 2);

console.log(squaredNumbers);
Output:

csharp
Copy code
[1, 4, 9, 16, 25]
Challenge 2:


Write a JavaScript program that utilizes the .filter method to filter an array of strings. Create an array of strings and use .filter to retrieve only the strings that have a length greater than 5. Finally, print the filtered array.

Expected Output:

The expected output of the program should be the filtered array of strings.


Challenge 3:

Write a JavaScript program that demonstrates the usage of various built-in methods like .pop, .push, .slice, .split, .indexOf, .unshift, .shift, and .reverse. Create an array of strings and perform the following operations:

Use .pop to remove the last element from the array.
Use .push to add a new element to the end of the array.
Use .slice to create a new array with a subset of elements from the original array.
Use .split to split a string into an array of substrings.
Use .indexOf to find the index of a specific element in the array.
Use .unshift to add a new element to the beginning of the array.
Use .shift to remove the first element from the array.
Use .reverse to reverse the order of elements in the array.
Finally, print the modified array after each operation.

use this arry:

let fruits = ['apple', 'banana', 'kiwi', 'orange'];

Expected Output:

The expected output of the program should be the modified array after each operation.



REACT STATE, PROPS, FUNCTIONAL PROPS, INPUT AND EVENTS CHALLENGE

STATE:

Button Click Counter: Create a button component that receives a function as a prop. Whenever the button is clicked, call the function passed as a prop and increment a counter using state. Stateful Counter: Implement the handleIncrement and handleDecrement functions to update the count state when the corresponding buttons are clicked. Display the current count value on the screen.

Form Submission Handler: Create a form component that receives a submit handler function as a prop. When the form is submitted, call the handler function and display a success message dynamically. Toggle Button: Implement the toggle functionality using state. Update the button text and background color based on the current state. When clicked, the button should switch between "ON" and "OFF" states.

PROPS
Card Component: Create a reusable card component that receives props for title, image, and content. Use props to display the information dynamically. Utilize props to display the provided title, image, and content dynamically. Use the props passed to the component to render a reusable card.

Data Table: Create a component that receives an array of data objects as props. Render a table dynamically with rows representing each data object and columns representing the properties of each object. Iterate over the array of data objects received as props and dynamically render a table with rows representing each data object and columns representing their properties.


FUNCTIONAL PROPS

Parent-Child Communication: Create a parent component that manages a state value. Pass a function as a prop to a child component and allow the child component to update the parent's state value.  Pass a function as a prop from the parent component to the child component. Implement the child component to call the function and update the parent's state value.

EVENTS

Click Counter: Create a component with a button. Implement a click event handler that increments a counter using state whenever the button is clicked.  Implement the click event handler to increment a counter using state whenever the button is clicked. Display the current count value on the screen.


RUBY CONDITIONALS

Write a Ruby program that demonstrates the concepts of method definition, local variables, conditional statements, user input, and string manipulation. The program should ask the user for their name, and then determine whether the name starts with the letter 'A'. If it does, it should print "Name starts with 'A'." Otherwise, it should print "Name does not start with 'A'."

Expected Output:
Please enter your name:
Alice

Name starts with 'A'.

Explanation:
The program prompts the user to enter their name. In this case, the user entered "Alice". Since the name starts with the letter 'A', the program outputs "Name starts with 'A'."

RUBY BLOCKS AND ITERABLES 

Challenge:
Write a Ruby program that takes an array of numbers and outputs the sum of the even numbers.

Expected Output:
The sum of the even numbers is 20.

Explanation:
The program will define a custom method that takes an array as an argument. Inside the method, you need to use a Ruby block to iterate over each element of the array and calculate the sum of the even numbers. Finally, print the sum as the output.

Note: The expected output may vary depending on the input array.

RUBY HASES

Challenge:

Write a Ruby program that demonstrates the use of hashes and their similarities to JavaScript objects. Your program should define a hash with key-value pairs representing information about a person. The program should then output the values associated with specific keys and demonstrate the accepted syntax of a Ruby hash.

Expected Output:

The expected output of the program should be:

makefile
Copy code
Name: John Doe
Age: 25
Occupation: Software Engineer

RUBY CLASSES AND OBJECTS

Challenge:

Write a Ruby program that demonstrates the use of classes, instance variables, getter methods, setter methods, the initialize method, and the attr_accessor attribute. Your program should define a custom class representing a person, with instance variables for name and age. It should also include getter and setter methods for these variables and use the initialize method to set their initial values. Finally, the program should create a new person object that requires name and age arguments in the initialize method.

Expected Output:

The expected output of the program should be:

makefile
Copy code
Name: John Doe
Age: 25

Challenge:

Write a Ruby program that demonstrates inheritance, method overriding, and the super keyword. Your program should define a base class called "Animal" with a method named sound. The program should then define two derived classes, "Cat" and "Dog," that inherit from the "Animal" class. Each derived class should override the sound method to produce a specific sound for the respective animal. Finally, the program should create instances of both the "Cat" and "Dog" classes and call the sound method on each instance.

Expected Output:

The expected output of the program should be:

yaml
Copy code
The cat says: Meow!
The dog says: Woof!

RUBY INHERITANCE

Challenge:

Create two classes, "Vehicle" and "Car," with an inheritance relationship between them. The "Vehicle" class should have a method named drive that outputs a generic message. The "Car" class should inherit from "Vehicle" and override the drive method to output a specific message for a car being driven.

Expected Output:

The expected output of the program should be:

css
Copy code
Driving a vehicle...
Driving a car...

Challenge:

Create two classes, "Shape" and "Rectangle," with an inheritance relationship between them. The "Shape" class should have an instance variable named name and a method named display_name that outputs the name of the shape. The "Rectangle" class should inherit from "Shape" and override the display_name method to prepend "Rectangle: " to the name of the shape. Additionally, demonstrate that instance variables are not inherited by child classes.

Expected Output:

The expected output of the program should be:

mathematica
Copy code
Shape: Circle
Rectangle: Square