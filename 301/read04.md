# Forms

## Controlled Components

- An input form element whose value is controlled by React in this way is called a “controlled component

### The textarea Tag

- In React, a `<textarea>` uses a **value** attribute instead. This way, a form using a `<textarea>` can be written very similarly to a form that uses a single-line input:

### The select Tag

- React, instead of using this selected attribute, uses a value attribute on the root select tag. This is more convenient in a controlled component because you only need to update it in one place.

### Handling Multiple Inputs

- When you need to handle multiple controlled input elements, you can add a name attribute to each element and let the handler function choose what to do based on the value of event.target.name.

### Alternatives to Controlled Components

- Fully-Fledged Solutions
- if you’re looking for a complete solution including validation, keeping track of the visited fields, and handling form submission, Formik is one of the popular choices. However, it is built on the same principles of controlled components and managing state — so don’t neglect to learn them
