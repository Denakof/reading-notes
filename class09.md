# forms

![img](https://images.slideplayer.com/23/6640686/slides/slide_10.jpg)

![img](https://disenowebakus.net/en/images/articles/forms-html-examples-styles-css-for-controls.jpg)

![img](https://miro.medium.com/max/2560/1*fETSg7vQPYlfUaVa49f8vg.png)

![img](https://sheetswithmaxmakhrov.files.wordpress.com/2018/08/form31.png?w=676)

![img](https://wpforms.com/wp-content/uploads/2019/08/new-custom-style-wpforms-submit-button.jpg)

-Whenever you want to c XX ollect information from visitors you will need a form, which lives inside a `<form>` element.

- Information from a form is sent in name/value pairs.
- Each form control is given a name, and the text the user types in or the values of the options they select
are sent to the server.
- HTML5 introduces new form elements which make it easier for visitors to fill in forms.

![img](https://images.squarespace-cdn.com/content/v1/5439bf1ee4b039cd17f4e1ed/1422467072216-QK1W3VN5HE7NMDN303ZG/ke17ZwdGBToddI8pDm48kKkU_AQeiAltHXXQXgvuqtpZw-zPPgdn4jUwVcJE1ZvWQUxwkmyExglNqGp0IvTJZUJFbgE-7XRK3dMEBRBhUpyYriKMfsU5Rtlrj8uei-CdCssQdl6xj84lz7KlT3CrYoDgAV1UvFo3sYnHBElVWa4/badbullets)

![img](https://i.ytimg.com/vi/u58vfl571n4/maxresdefault.jpg)

- width to set the width of the table padding to set the space
between the border of each table cell and its content
text-transform to convert the content of the table headers to uppercase
- letter-spacing, font-size to add additional styling to the content of the table headers border-top, border-bottom to set borders above and below the table headers.

- text-align to align the writing to the left of some table cells and to the right of the others background-color to change the background color of the alternating table rows
- :hover to highlight a table row when a user's mouse goes over it

![img](https://slidetodoc.com/presentation_image_h/c96de19d42ac1e5c739a4e561930c174/image-22.jpg)

- show :This shows the borders of any empty cells.

- hide This hides the borders of any empty cells.
- inherit If you have one table nested inside another, the inherit value instructs the table cells to obey the rules of the containing table.
- In the first table on the left, you can see that the border of the empty cell is showing. In the second table, it is hidden.

![img](https://miro.medium.com/max/1838/0*wJjCeBZWkS2LEHhG.png)

![img](https://i.stack.imgur.com/2Ce2d.png)

- In addition to the CSS p XX roperties covered in other chapters which work with the contents of all elements, there are several others that are specifically used to control the appearance of lists, tables, and forms.
- List markers can be given different appearances using the list-style-type and list-style image properties.
- Table cells can have different borders and spacing in different browsers, but there are properties you can use to control them and make them more consistent.
- Forms are easier to use if the form controls are vertically aligned using CSS.
- Forms benefit from styles that make them feel more interactive

## HTML events are handled by JavaScript. ... onclick: It is triggered when an HTML element is clicked. onmouseover: It is triggered when the mouse is moved over a HTML element. onmouseout: It is triggered when the mouse is moved out of a HTML element

1. Select the element node(s) you want the script to respond to

2. Indicate which event on the selected node(s) will trigger the response

3. State the code you want to run when the event occurs

### THREE WAYS TO BIND AN EVENT TO AN ELEMENT

- Event handlers let you indicate which event you are waiting for on any particular element. There are three types of event handlers.

![img](https://data-flair.training/blogs/wp-content/uploads/sites/2/2019/07/Ways-of-Using-JavaScript-Events-1200x675.png)

- All modern browsers understand this way of creating an event handler, but you can only attach one function to each event handler.

- USING DOM EVENT HANDLERS:Event listeners are a more recent approach to handling events. They can deal with more than one function at a time but they are not supported in older browsers

USING PARAMETERS WITH EVENT HANDLERS & LISTENERS

- Because you cannot have parentheses after the function names in event handlers or listeners, passing arguments requires a workaround

- USING PARAMETERS WITH EVENT LISTENERS

- SUPPORTING OLDER VERSIONS OF IE

### IES-8 had a different event model and did not support addEventL i stener() but you can provide fallback code to make event listeners work with older versions of IE

![img](https://www.slideteam.net/media/catalog/product/cache/960x720/e/v/event_flow_presentation_portfolio_Slide01.jpg)

- When an event occurs, the event object tells you information about the event, and the element it happened upon

- EVENT DELEGATION Creating event listeners for a lot of elements can slow down a page, but event flow allows you to listen for an event on a parent element

- CHANGING DEFAULT BEHAVIOR The event object has methods that change: the default behavior of an element and how the element's ancestors respond to the event.

- WHICH ELEMENT DID AN EVENT OCCUR ON?

#### When calling a function, the event object's target property is the best way to determine which element the event occurred on. But you may see the approach below used; it relies on the this keyword

- DIFFERENT TYPES OF EVENTS

##### In the rest of the chapter, you learn about the different types of events you can respond to

- USER INTERFACE EVENTS

#### User interface CUI) events occur as a result of interaction with the browser window rather than the HTML page contained within it, e.g., a page having loaded or the browser window being resized

- FOCUS & BLUR EVENTS

##### The HTML elements you can interact with, such as links and form elements, can gain focus. These events fire when they gain or lose focus

- KEYBOARD EVENTS

##### The keyboard events are fired when a user interacts with the keyboard (they fire on any kind of device with a keyboard)

- FORM EVENTS

###### There are two events that are commonly used with forms. In particular you are likely to see submit used in form validation

#### MUTATION EVENTS & OBSERVERS

##### Whenever elements are added to or removed from the DOM, its structure changes. This change triggers a mutation event

- Events are the browser's way of indicating when something has happened (such as when a page has finished loading or a button has been clicked).
- Binding is the process of stating which event you are waiting to happen, and which element you are waiting for that event to happen upon.
- When an event occurs on an element, it can trigger a JavaScript function. When this function then changes the web page in some way, it feels interactive because it has responded to the user.
- You can use event delegation to monitor for events that happen on all of the children of an element.
- The most commonly used events are W3C DOM events, although there are others in the HTMLS specification as well as browser-specific events