## JavaScript 

### Chapter 1
- JavaScript can: though typically first it reacts then access, modifies and programs 
    1. Access the content of the page
    2. Modify the content of hte page
    3. Program rules or insturctions the browser can floow
    4. React to events triggered by the user or browser 
- Scripts can act like a manual
    - A script is just a series of short instructions, eache is performed in order to solve the problem at hand
- To write a script you must first state your goal, what puzzle is the computer going to solve? 
- Next, design the script: Cut the goal down into small solvable pieces 
- Code each step:
    - Event: ie a button is clicked
    - input or output: happens in the button
    - a decision is made: if x- do ... else- ... 
    - a generic step is made: z is done with the input or output 
    - output is given: from the generic step taken  

### Expressions and Operators 
- There are two types of expressions
    - expressions that just assign a calue to a variable: ie var color = 'beige';
    - Expressions that use two or more values to return a single value: var area = 3 * 2; 
- Expressions rely on operators; they are a symbol that does one thing and allows programmers to create a single value from one or more values: '='
    - '+' adds one value to another 
    - '-' subtracts one value from antoher 
    - '/' divides two values 
    - '*' multiplires two values 
    - '++' adds one to the curren nuber 
    - '--' subracts one from the current number 
    - '%' divides two values and returns the remainder 
- when thre are several arithmetic operations in one expression, the mathimatical heierarchy remains: mult and div first, then add and subtract
- When two variables are added together, it is called CONCATENATION:
    var firstname=
    var lastname=
    var fullname= firstname + lastname

### Functions
- A function is a seriese of statments grouped together to perfom a specific task. If different parts of a script repeat the same task, you can ruse the fuction, rather than repeating the same set of staments. 
- A function must be given a name if it is going to be called in to work. A good name should accuratly and clearly describe the fuction of the function.
- The code for the function is packeged up in a code block. The code block is wrapped up in curly braces. 
- A parameter is a piece of imformation passed to a function, ie the width and height of a box to calcuate the area. H and W are the paramters 
- The Return Value is the answer the fucntion gives you. 
- The name of the fucntion can be used to call the code over and over again, while the code only needs to be written once
- When a fuction is called with parameters, you specify the values it should use in the parentheses that follow its name. HTe values are called arguments, and thycan be provided as values or variables: getArea(wallWidth, wallHeight)
