# class 06

## Functions methods and objects

### WHAT IS AN OBJECT?

#### Objects group together a set of variables and functions to create a model of a something you would recognize from the real world. In an object, variables and functions take on new names

![img](https://i0.wp.com/testnbug.com/wp-content/uploads/2015/03/Mobile-phones.jpg)

- Like variables and named functions, properties and methods have a name and a va lue. In an object, that name is called a key.

- An object cannot have two keys with the same name. This is because keys are used to access their corresponding values.

- The value of a property can be a string, number, Boolean, array, or even another object. The va lue of a method is always a function.

- Programmers use a lot of name/value pairs

- HTML uses attribute names and values.

- CSS uses property names and values. In JavaScript:

- Variables have a name and you can assign them a value of a string, number, or Boolean.
- Arrays have a name and a group of values. (Each item in an array is a name/value pair because it has an index number and a value.)
- Named functions have a name and value that is a set of statements to run if the function is called.
- Objects consist of a set of name/value pairs (but the names are referred to as keys).

![img](http://www.techbubbles.com/wp-content/uploads/2009/01/json3-thumb.png)

![img](data:image/png;base64,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)

##### CREATING· OBJECTS USING LITERAL NOTATION

![img](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSLW7wc8P4EZOg3ECTUNDhl3mZtoK_yqTBUTQ&usqp=CAU)

![img](https://miro.medium.com/max/1074/1*Nnb4H4tOORSoNvCItWZTpg.png)

#### document object model

#### The Document Object Model (DOM) specifies how browsers should create a model of an HTML page and how JavaScript can access and update the contents of a web page while it is in the browser window

![img](https://upload.wikimedia.org/wikipedia/commons/5/58/Dom_tree.png)

#### WORKING WITH THE DOM TREE

- STEP 1: ACCESS THE ELEMENTS
- STEP 2: WORK WITH THOSE ELEMENTS  

- DOM queries may return one element, or they may return a Nodelist, which is a collection of nodes.

![img](https://i.stack.imgur.com/ypZlJ.png)
![img](https://community.dynamics.com/resized-image/__size/320x240/__key/communityserver-discussions-components-files/117/pastedimage1600121275551v3.png
)
![img](https://www.codegrepper.com/codeimages/how-to-define-a-button-in-queryselector.png)

![img](https://res.cloudinary.com/raymons/image/upload/w_1600/q_auto,f_auto/loop-over-nodelist-queryselectorall-javascript.png)

##### When you have an element node, you can select another element in relation to it using these five properties. This is known as traversing the DOM

![img](https://www.tutorialsteacher.com/Content/images/jquery/jq-traversing-methods.png)

##### Traversing the DOM can be difficult because some browsers add a text node whenever they come across whitespace between elements

##### first and last sibling

![img](https://i.stack.imgur.com/9zp3z.png)

![img](https://1.bp.blogspot.com/-KEZs6LANRQY/X3ld_7bDg_I/AAAAAAAAB8A/vchf_tHcl8wKHI4a4fvc_y2gsFQO8Ut6ACLcBGAsYHQ/s735/dom3.jpg)

![img](https://javascript.info/article/basic-dom-node-properties/dom-class-hierarchy.svg)

##### When you select a text node, you can retrieve or amend the content of it using the node Va 1 ue property

##### ACCESS & UPDATE TEXT WITH TEXTCONTENT (& INN ERTEXT)

##### The textCon tent property allows you to collect or update just the text that is in the containing element (and its children)

##### ACCESS & UPDATE TEXT & MARKUP WITH INNERHTML

- Using the i nnerHTML property, you can access and amend the contents of an element, including any child elements.

- UPDATE TEXT & MARKUP

- ACCESS & UPDATE TEXT & MARKUP WITH INNERHTML

![img](https://www.tutorialsteacher.com/Content/images/jquery/manipulation-methods.png)

1. CREATE THE ELEMENT `createElement ()`

2. GIVE IT CONTENT `createTextNode()`

3. ADD IT TO THE DOM `appendChild()`

##### ADDING AN ELEMENT TO THE DOM TREE

- createEl ement () creates anelement that can be added to the DOM tree, in this case an empty ` <li> `element for the list

- This new element is stored inside a variable called newEl until it is attached to the DOM tree later on.

- createTextNode() allows you to create a new text node to attach to an element. It is stored in a variable called newText.

##### REMOVING AN ELEMENT FROM THE DOM TREE

![img](https://www.codegrepper.com/codeimages/delete-element-from-dom-javascript.png)

#### COMPARING TECHNIQUES: UPDATING HTML CONTENT

- **document.write()**

- ADVANTAGES :It is a quick and easy way to show beginners how content can be added to a page.

- DISADVANTAGES : It only works when the page initially loads.
• If you use it after the page has loaded it can:

1. Overwrite the whole page
2. Not add the content to the page
3. Create a new page

• It can cause problems with XHTML pages that are strictly validated.
• This method is very rarely used by programmers these days and is genera lly frowned upon.

- **element.innerHTML**
- The i nnerHTML property lets you get/update the entire content of any element (including markup) as a string

- ADVANTAGES
- You can use it to add a lot of new markup using less code than DOM manipulation methods.
- It can be faster than DOM manipulation when adding a lot of new elements to a web page.
- It is a simple way to remove all of the content from one element (by assigning it a blank string).

- DISADVANTAGES
- It should not be used to add content that has come from a user (such as a username or blog comment), as it can pose a significant security risk which is discussed over the next four pages.
- It can be difficult to isolate single elements that you want to update within a larger DOM fragment.
- Event handlers may no longer work as intended

##### DOM MANIPULATION

- ADVANTAGES
- It is suited to changing one element from a DOM
fragment where there are many siblings.
- It does not affect event handlers.
- It easily allows a script to add elements incrementally (when you do not want to alter a lot of code at once).

- DISADVANTAGES

- If you have to make a lot of changes to the content of a page, it is slower than i nnerHTML.
- You need to write more code to achieve the same thing compared with i nnerHTML.

##### CROSS-SITE SCRIPTING (XSS) ATTACKS

- If you add HTML to a page using i nnerHTML (or several jQuery methods), you need to be aware of Cross-Site Scripting Attacks or XSS; otherwise, an attacker could gain access to your users' accounts.

![img](https://portswigger.net/web-security/images/cross-site-scripting.svg)

##### REMOVING ATTRIBUTES To remove an attribute from an element, first select the element, then call removeAtt r i bute () . It has one parameter: the name of the attribute to remove

##### EXAMINING THE DOM IN CHROME Modern browsers come with tools that help you inspect the page loaded in the browser and understand the structure of the DOM tree

### EXAMINING THE DOM IN FIREFOX

- Firefox has similar built-in tools, but you can also download a DOM inspector tool that shows the text nodes.

- The browser represents the page using a DOM tree. DOM trees have four types of nodes: document nodes,
- element nodes, attribute nodes, and text nodes.
- You can select element nodes by their id or class attributes, by tag name, or using CSS selector syntax.
- Whenever a DOM query can return more than one
- node, it will always return a Nadel i st.
 From an element node, you can access and update its content using properties such as textContent and
- i nnerHTML or using DOM manipulation techniques.
- An element node can contain multiple text nodes and child elements that are siblings of each other.
- In older browsers, implementation of the DOM is inconsistent (and is a popular reason for using jQuery)
- Browsers offer tools for viewing the DOM tree .
