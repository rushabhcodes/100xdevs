# Properties of JS
	- ## 1. Interpreted
		- JavaScript is an interpreted language, meaning it's executed 
		  id:: 66af93d0-e1fc-4299-91c5-c6cd067c8813
		  line-by-line at runtime by the JavaScript engine in the browser or 
		  server environment, rather than being compiled into machine code 
		  beforehand.
	- ## 2. Dynamically Typed
		- Variables in JavaScript are not bound to a specific data type. Types are
		   determined at runtime and can change as the program executes
	- ## 3. Single threaded
		- JavaScript executes code in a single-threaded environment, meaning it 
		  processes one task at a time. We will dive deeper into this next week.
	- ## 4. Garbage collected
		- JavaScript automatically manages memory allocation and deallocation 
		  through garbage collection, which helps prevent memory leaks by 
		  automatically reclaiming memory used by objects no longer in use.
		- Syntax of JS
- # Syntax of JavaScript
	- #### 1. **Variables**
		- Variables are used to store data. In JavaScript, you declare variables using `var`, `let`, or `const`.
		- ```js
		  	let name = "John";     // Variable that can be reassigned
		  const age = 30;        // Constant variable that cannot be reassigned
		  var isStudent = true;  // Older way to declare variables, function-scoped
		  ```
	- #### 2. Data types
		- ```js
		  	let number = 42;             // Number
		  let string = "Hello World";  // String
		  let isActive = false;        // Boolean
		  let numbers = [1, 2, 3];     // Array
		  ```
		- ##### Objects
			- An object in JavaScript is a collection of `key-value pairs`, where each `key` is a string and each `value` can be any valid JavaScript data type, including another object.
			- ```js
			  let user = {
			  name: "Harkirat",
			  age: 19
			  }
			  - console.log("Harkirats age is " + user.age);
			  ```
		- ##### Arrays
			- Arrays let you group data together
			- ```js
			  const users = ["harkirat", "raman", "diljeet"];
			  const tatalUsers = users.length;
			  const firstUser = users[0];
			  ```
	- #### 3. **Operators**
		- ```js
		  let sum = 10 + 5;          // Arithmetic operator
		  let isEqual = (10 === 10); // Comparison operator
		  let isTrue = (true && false); // Logical operator
		  ```
	- #### 4. **Functions**
		- ```js
		  // Function declaration
		  function greet(name) {
		    return "Hello, " + name;
		  }
		  
		  // Function call
		  let message = greet("John"); // "Hello, John"
		  ```
	- #### 5. If/Else
		- ```js
		  if (age >= 18) {
		    console.log("You are an adult.");
		  } else {
		    console.log("You are a minor.");
		  }
		  ```
	- #### 6. Loops
		- ```js
		  // For loop
		  for (let i = 0; i < 5; i++) {
		    console.log(i); // Outputs 0 to 4
		  }
		  
		  // While loop
		  let j = 0;
		  while (j < 5) {
		    console.log(j); // Outputs 0 to 4
		    j++;
		  }
		  ```
		-
- Ref:
	- [slides](https://projects.100xdevs.com/tracks/javascript-1/Javascript-101-1)
	- ![web2day2.png](../assets/web2day2_1722784766057_0.png)
-