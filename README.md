# Revision Quiz
javascript
# What does DOM stand for?
✅ a) Document Object Model


# Which method is used to select an element by its ID?
✅ c) getElementById()


# What does document.querySelector(".box") select?
✅ b) The first element with class "box"


# How do you change the text of an element with ID "message"?
✅ d) document.getElementById("message").innerText = "Hello"


# What is the purpose of innerHTML?
✅ c) To get or set the HTML content of an element


# What is an event in JavaScript?
✅ b) A user or browser action


# Which event occurs when a user clicks on an HTML element?
✅ c) onclick


# How can you add a click event to a button in JavaScript?
✅ b) addEventListener("click")


# What does event.preventDefault() do?
✅ b) Stops default action like form submission


# Which method is used to attach an event handler?
✅ c) addEventListener()


# What does Math.random() return?
✅ c) A number between 0 and 1


# How do you get a random integer from 1 to 10?
✅ c) Math.floor(Math.random() * 10) + 1


# What is the output range of Math.random()?
✅ c) 0 (inclusive) to 1 (exclusive)

# Which function converts a float to an integer?
✅ b) Math.floor()


# What will Math.floor(4.9) return?
✅ b) 4


# Variables

# How do you declare a variable in JavaScript?
✅ d) All of the above


# Which variable type allows reassignment?
✅ b) let


# Which keyword declares a block-scoped variable?
✅ c) let


# What will happen if you use a variable without declaring it?
✅ b) It becomes a global variable


# Which keyword creates a constant in JavaScript?
✅ c) const


# Functions

# What is a function?
✅ b) A reusable block of code


# How do you define a function named sayHello?
✅ a) function sayHello() {}


# How do you call a function in JavaScript?
✅ c) sayHello()


# What is the keyword to return a value from a function?
✅ c) return


# What is a parameter in a function?
✅ b) A variable passed into a function


# Mixed Concepts

# What will typeof "hello" return?
✅ a) string


# What does console.log() do?
✅ c) Outputs messages to the browser console


# How do you write a comment in JavaScript?
✅ b) // comment


# Which of these is a valid function expression?
✅ b) let add = function(x, y) { return x + y; }


# What does NaN mean?
✅ a) Not a Number


# Which method is used to convert a string to a number?
✅ a) parseInt()


# 🧠 Bonus Conceptual Questions
# Why is using let safer than var?
Explanation: let is block-scoped, reducing the risk of variable collisions and unexpected behaviors associated with var's function scope.

# What is the main benefit of separating JavaScript from HTML?
𝐄𝐱𝐩𝐥𝐚𝐧𝐚𝐭𝐢𝐨𝐧:  It promotes cleaner code, better maintainability, and separation of concerns.

# Why is Math.random() useful in games or UI effects?
𝐄𝐱𝐩𝐥𝐚𝐧𝐚𝐭𝐢𝐨𝐧: It introduces randomness, enhancing interactivity and unpredictability in applications.

# What happens if two event listeners are attached to the same element?
𝐄𝐱𝐩𝐥𝐚𝐧𝐚𝐭𝐢𝐨𝐧: Both listeners will execute in the order they were added.

# Why should we use functions to organize code?
𝐄𝐱𝐩𝐥𝐚𝐧𝐚𝐭𝐢𝐨𝐧:  Functions promote reusability, modularity, and clarity in code structure.

# 🛠️ Practical Understanding (Optional)
# Why does Math.floor(Math.random() * 10) only go up to 9?
Explanation: Math.random() returns values from 0 up to but not including 1. Multiplying by 10 gives a range from 0 up to but not including 10. Applying Math.floor then yields integers from 0 to 9.

# What does addEventListener("click", function(){...}) do?
Explanation: It attaches a click event handler to an element, executing the provided function when the element is clicked.

# Why is it helpful to give buttons IDs or classes in the DOM?
Explanation: Assigning IDs or classes allows for easy selection and manipulation of elements via JavaScript or CSS.

# Can you assign a function to a variable in JavaScript? Why?
Explanation: Yes; functions are first-class objects in JavaScript, allowing them to be assigned to variables, passed as arguments, or returned from other functions.

# What’s the difference between a function declaration and expression?
Explanation: Function declarations are hoisted, meaning they can be called before they're defined in the code. Function expressions are not hoisted and are defined when the interpreter reaches them during execution.

