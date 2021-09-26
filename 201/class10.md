# ch10

- ORDER OF EXECUTION

![img](https://miro.medium.com/max/3630/1*ddKOVPd0nh4-3l9QisgJnQ.png)

## To find the source of an error, it helps to know how scripts are processed. The order in which statements are executed can be complex; some tasks cannot complete until another statement or function has been run

![img](https://miro.medium.com/max/1592/0*ryPdDzB_jghiVi2e.png)

- EXECUTION CONTEXT & HOISTING

- 1: PREPARE
• The new scope is created
• Variables, functions, and arguments are created
• The value of the this keyword is determined

- 2: EXECUTE
• Now it can assign values to variables
• Reference functions and run their code
• Execute statements

- UNDERSTANDING SCOPE

- In the interpreter, each execution context has its own va ri ables object. It holds the variables, functions, and parameters available within it. Each execution context can also access its parent's v a ri ables object

- UNDERSTANDING ERRORS
- If a JavaScript statement generates an error, then it throws exception. At that point, the interpreter stops and looks for exception-handling code

- ERROR OBJECTS

### Error objects can help you find where your mistakes are and browsers have tools to help you read them

- HOW TO DEAL WITH ERRORS

- Now that you know what an error is and how the browser treats them, there are two things you can do with the errors.

1. DEBUG THE SCRIPT TO FIX ERRORS
2. HANDLE ERRORS GRACEFULLY

- A DEBUGGING WORKFLOW

- Debugging is about deduction: eliminating potential causes of an error. Here is a workflow for techniques you will meet over the next 20 pages. Try to narrow down where the problem might be, then look for clues.

- BROWSER DEV TOOLS & JAVASCRIPT CONSOLE

- The JavaScript console will tell you when there is a problem with a script, where to look for the problem, and what kind of issue it seems to be

- HOW TO LOOK AT ERRORS IN CHROME

![img](https://img.webnots.com/2018/01/Error-Connection-Closed-in-Chrome.png)

- HOW TO LOOK AT ERRORS IN FIREFOX

![img](https://user-media-prod-cdn.itsre-sumo.mozilla.net/uploads/gallery/images/2019-03-23-05-32-07-09259b.png)

- WRITING FROM THE SCRIPT TO THE CONSOLE

- Browsers that have a console have a console object, which has several methods that your script can use to display data in the console. The object is documented in the Console API

- LOGGING DATA TO THE CONSOLE

- MORE CONSOLE METHODS To differentiate between the types of messages you write to the console, you can use three different methods. They use various colors and icons to distinguish them.

- GROUPING MESSAGES

 1. If you want to write a set of related data to the console, you can use the console. group () method to group the messages together. You can then expand and contract the results.

- WRITING TABULAR DATA In browsers that support it, the console. table () method lets you output a table showing:
• objects
• arrays that contain other objects or arrays

- WRITING ON A CONDITION Using the console. assert() method, you can test if a condition is met, and write to the console only if the expression evaluates to false.

- BREAKPOINTS You can pause the execution of a script on any line using breakpoints. Then you can check the va lues stored in variables at that point in time.

- STEPPING THROUGH CODE If you set multiple breakpoints, you can step through them one-by-one to see where values change and a problem might occur.

- CONDITIONAL BREAKPOINTS

- You can indicate that a breakpoint should be triggered only if a condition that you specify is met. The condition can use existing variables.

![img](https://www.valentinog.com/blog/static/199d49f6c5443ce3336c96cf4e2395f8/c1b63/error-handling-javascript.png)

- If you know your code might fail, use try, catch, and finally. Each one is given its own code block.

- THROWING ERRORS

- If you know something might cause a problem for your script, you can generate your own errors before the interpreter creates them.

- THROW ERROR FOR NaN If you try to use a string in a mathematical operation (other than in addition), you do not get an error, you get a special value called NaN (not a number).

- DEBUGGING TIPS

- Here are a selection of practical tips that you can try to use when debugging your scripts.

- COMMON ERRORS

- Here is a list of common errors you might find with your scripts

- If you understand execution contexts (which have two stages) and stacks, you are more likely to find the error in your code.

- Debugging is the process of finding errors. It involves a process of deduction.
- The console helps narrow down the area in which the error is located, so you can try to find the exact error.

- JavaScript has 7 different types of errors. Each creates its own error object, which can tell you its line number and gives a description of the error.
- If you know that you may get an error, you can handle it gracefully using the try, catch, finally statements. Use them to give your users helpful feedback.
