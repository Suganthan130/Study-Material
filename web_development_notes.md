# Web Development Notes

## Unit 1: HTML Basics

### Notes
- **HTML (Hypertext Markup Language)**: The standard markup language for creating web pages.
  - **HTML5**: The latest version, indicated by `<!DOCTYPE html>`.
  - **Common Elements**:
    - `<html>`: Root element.
    - `<head>`: Contains meta-information, title, links to stylesheets, etc.
    - `<body>`: Contains the content of the document.
    - `<a>`: Defines a hyperlink.
    - `<p>`: Defines a paragraph.
    - `<img>`: Embeds an image.
    - `<div>`: Defines a division or section.
    - `<span>`: Used for grouping inline-elements.
  - **Attributes**: Provide additional information about elements (e.g., `class`, `id`, `src`, `href`).

### Model Questions
1. What is the purpose of the DOCTYPE declaration in HTML?
2. List and describe five common HTML elements and their attributes.

---

## Unit 2: CSS Basics

### Notes
- **CSS (Cascading Style Sheets)**: Used to style HTML elements.
  - **Syntax**: `selector { property: value; }`
  - **Common Selectors**:
    - Type Selector: Selects elements by name (e.g., `p { ... }`).
    - Class Selector: Selects elements with a specific class (e.g., `.class-name { ... }`).
    - ID Selector: Selects an element with a specific ID (e.g., `#id-name { ... }`).
  - **External Style Sheet**: Linked using `<link rel="stylesheet" type="text/css" href="styles.css" />`.

### Model Questions
1. How do you link an external CSS file to an HTML document?
2. Explain the difference between class and ID selectors in CSS.

---

## Unit 3: JavaScript Basics

### Notes
- **JavaScript**: A scripting language used to create dynamic content on web pages.
  - **Common Methods**:
    - `document.getElementById(id)`: Selects an element by ID.
    - `document.getElementsByClassName(class)`: Selects elements by class name.
    - `document.querySelector(selector)`: Selects the first element that matches a CSS selector.
  - **Event Handling**: Responding to user actions (e.g., `onclick`, `onload`).

### Model Questions
1. How do you select an element with the ID `myElement` in JavaScript?
2. What is an event handler? Give an example.

---

## Unit 4: AJAX and JSON

### Notes
- **AJAX (Asynchronous JavaScript and XML)**: Allows web pages to be updated asynchronously by exchanging data with a web server.
  - **XMLHttpRequest Object**: Used to interact with servers.
    - Methods: `open()`, `send()`, `setRequestHeader()`.
    - Properties: `responseText`, `status`.
- **JSON (JavaScript Object Notation)**: A lightweight data interchange format.

### Model Questions
1. What is AJAX and why is it used?
2. How do you create an instance of `XMLHttpRequest` and send a GET request?

---

## Unit 5: PHP and MySQL

### Notes
- **PHP (Hypertext Preprocessor)**: A server-side scripting language.
  - **Super Globals**: Built-in variables that are always accessible (e.g., `$_SESSION`, `$_POST`, `$_GET`).
- **MySQL**: A relational database management system.
  - **Common Functions**: 
    - `mysqli_connect()`
    - `mysqli_query()`
    - `mysqli_fetch_assoc()`
    - `mysqli_close()`

### Model Questions
1. What is the purpose of the `$_SESSION` super global in PHP?
2. How do you connect to a MySQL database in PHP?

---

## Unit 6: Networking Basics

### Notes
- **Twisted Pair Cables**: UTP (Unshielded Twisted Pair) and STP (Shielded Twisted Pair).
- **High-Speed Network Media**: Fiber Optic Cable is commonly used.
- **ARPANET**: The precursor to the modern internet, stands for Advanced Research Projects Agency Network.

### Model Questions
1. What is the difference between UTP and STP cables?
2. What does ARPANET stand for and why is it significant?
