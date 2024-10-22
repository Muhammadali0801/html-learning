# HTML Forms

This document explains the structure and elements of HTML forms, which are used to collect user input and send it to a server for processing.

---

### 1. The `<form>` Element

The `<form>` element is the container for input elements, such as text fields, checkboxes, radio buttons, and more. The form element includes attributes such as `action` and `method`:

- **`action`**: Specifies the URL where the form data will be sent when the form is submitted.
- **`method`**: Specifies how the data will be sent. The common methods are:
  - `get`: Appends the form data to the URL in the form of name/value pairs.
  - `post`: Sends the form data as a block (more secure than `get`).

### 2. The `<input>` Element
The `<input>` element is used to create various input fields. It is a self-closing tag and can have different types:

type="text": Creates a single-line text input.
type="password": Creates a password field, where the characters are hidden.
type="radio": Creates a radio button, allowing the user to select only one option from a group.
type="checkbox": Creates a checkbox, allowing the user to select or deselect an option.
type="submit": Creates a submit button that sends the form data to the server.

### 3. The `<label>` Element
The `<label>` element is used to define labels for the form's input elements. It provides better accessibility by allowing users to click on the label to focus the corresponding input field. The for attribute in the `<label>` tag should match the id of the input element.

### 4. Radio Buttons and Checkboxes
Radio Buttons: Allow users to select one option from a group of predefined choices. Each radio button in a group should share the same name attribute to ensure only one can be selected.

Checkboxes: Allow users to select or deselect multiple options. Unlike radio buttons, multiple checkboxes can be selected at the same time.

### 5. The `<select>` and `<option>` Elements
The `<select>` element creates a drop-down list. The `<option>` elements inside the `<select>` define the available choices for the user.


### 6. The `<textarea>` Element
The `<textarea>` element is used for multi-line text input. It includes rows and cols attributes to control the visible size of the text area.

### 7. The `<button>` and `<input type="submit">` Elements
The `<input type="submit">` is used to submit the form data to the server. Alternatively, the `<button>` tag can also be used to create clickable buttons that can perform various actions.