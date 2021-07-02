# read03

1. What does .map() return?

- we use the map() function to take an array of numbers and double their values. We assign the new array returned by ma () to the variable doubled and log it

2. If I want to loop through an array and display each value in JSX, how do I do that in React?

- Rendering Multiple Components You can build collections of elements and include them in JSX using curly braces {}. Below, we loop through the numbers array using the JavaScript map() function. We return a <li> element for each item. Finally, we assign the resulting array of elements to listItems
- We include the entire listItems array inside a <ul> element, and render it to the DOM:

3. Each list item needs a unique __key__.

4. What is the purpose of a key?
. A “key” is a special string attribute you need to include when creating lists of elements.


5. What is the spread operator?

- InJavaScript, spread syntax refers to the use of an ellipsis of three dots (…) to expand an iterable object into the list of arguments.

List 4 things that the spread operator can do.
Copying an array
Concatenating or combining arrays
Using Math functions
Using an array as arguments
Adding an item to a list
Adding to state in React

Give an example of using the spread operator to combine two arrays.

` 
[...["😋😛😜🤪😝"]] // Array [ "😋😛😜🤪😝" ]
[..."🙂🙃😉😊😇🥰😍🤩!"] // Array(9) [ "🙂", "🙃", "😉", "😊", "😇", "🥰", "😍", "🤩", "!" ]

const hello = {hello: "😋😛😜🤪😝"}
const world = {world: "🙂🙃😉😊😇🥰😍🤩!"}

const helloWorld = {...hello,...world}
console.log(helloWorld) // Object { hello: "😋😛😜🤪😝", world: "🙂🙃😉😊😇🥰😍🤩!" } `

Give an example of using the spread operator to add a new item to an array.
`const fruits = ['🍏','🍊','🍌','🍉','🍍']
const moreFruits = [...fruits];
console.log(moreFruits) // Array(5) [ "🍏", "🍊", "🍌", "🍉", "🍍" ]
fruits[0] = '🍑'
console.log(...[...fruits,'...',...moreFruits]) //  🍑 🍊 🍌 🍉 🍍 ... 🍏 🍊 🍌 🍉 🍍`

Give an example of using the spread operator to combine two objects into one.
`const myArray = [`🤪`,`🐻`,`🎌`]
const yourArray = [`🙂`,`🤗`,`🤩`]
const ourArray = [...myArray,...yourArray]
console.log(...ourArray) // 🤪 🐻 🎌 🙂 🤗 🤩`

In the video, what is the first step that the developer does to pass functions between components?
creates a function wherever the state is that we are going to change.



In your own words, what does the increment function do?
function will loop through people array and find the required name and change it using map

How can you pass a method from a parent component into a child component?
using props

How does the child component invoke a method that was passed to it from a parent component?
by using state