What is a ‘call’?
The understanding of the call stack is vital to Asynchronous programming (which we will look at in a later article).

In Asynchronous JavaScript, we have a callback function, an event loop, and a task queue. The callback function is acted upon by the call stack during execution after the call back function has been pushed to the stack by the event loop.
How many ‘calls’ can happen at once?
1
What does LIFO mean?
The order in which elements come off a stack gives rise to its alternative name, LIFO (last in, first out). Additionally, a peek operation may give access to the top without modifying the stack. The name "stack" for this type of structure comes from the analogy to a set of physical items stacked on top of each other.

Draw an example of a call stack and the functions that would need to be invoked to generate that call stack.

A stack overflow occurs when there is a recursive function (a function that calls itself) without an exit point. The browser (hosting environment) has a maximum stack call that it can accomodate before throwing a stack error.


`function callMyself(){
  callMyself();
}

callMyself();`

The callMyself() will run until the browser throws a “Maximum call size exceeded”. And that is a stack overflow.

What causes a Stack Overflow?
A stack overflow occurs when there is a recursive function (a function that calls itself) without an exit point. The browser (hosting environment) has a maximum stack call that it can accomodate before throwing a stack error.

What is a ‘refrence error’?
This is as simple as when you try to use a variable that is not yet declared you get this type os errors.

What is a ‘syntax error’?
I know it’s in the name of the errors, but like it says itself, this occurs when you have something that cannot be parsed in terms of syntax, like when you try to parse an invalid object using JSON.parse.

What is a ‘range error’?
Try to manipulate an object with some kind of length and give it an invalid length and this kind of errors will show up.
`var foo= []
foo.length = foo.length -1 //
`
 Uncaught RangeError: Invalid array length
An array for instance cannot have a negative length, why would you mess with the array length? Some people use it to set an array to empty, something of the likes of:
What is a ‘tyep error’?
Like the name indicates, this types of errors show up when the types (number, string and so on) you are trying to use or access are incompatible, like accessing a property in an undefined type of variable.
This is probably the most frequent error in JS, trying to access a property/method thinking that bar is of the type object when in reality, since it hasn’t been declared yet, it’s undefined which doesn’t have any baz available.
The fix is simple, just make sure that bar exists before trying to access it, either by creating bar or by checking for undefined.

What is a breakpoint?
A breakpoint is a point in the program where the code will stop executing. For example, if the programmer amended the logic error in the trace table example they may wish to trigger a break point at line 5 in the algorithm.

What does the word ‘debugger’ do in your code?
A debugger is a software tool that can help the software development process by identifying coding errors at various stages of the operating system or application development. Some debuggers will analyze a test run to see what lines of code were not executed.
