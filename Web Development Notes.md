# Web Development Notes

## Unit 1: HTML Basics

### HTML Overview
- **HTML (Hypertext Markup Language)**: The core language used to create and design web pages.
  - **HTML5**: The most recent version, which supports advanced features for modern web applications.

### HTML Structure
- **DOCTYPE Declaration**: Specifies the HTML version and document type.
  ```html
  <!DOCTYPE html>
Basic HTML Document Structure:
html
Copy code
<!DOCTYPE html>
<html>
  <head>
    <meta charset="UTF-8">
    <title>Page Title</title>
    <link rel="stylesheet" href="styles.css">
    <script src="script.js"></script>
  </head>
  <body>
    <h1>Welcome to My Page</h1>
    <p>This is a paragraph.</p>
  </body>
</html>
Common HTML Elements
Headings:

html
Copy code
<h1>Main Heading</h1>
<h2>Subheading</h2>
Paragraphs:

html
Copy code
<p>This is a paragraph.</p>
Links:

html
Copy code
<a href="https://example.com">Visit Example</a>
Images:

html
Copy code
<img src="image.jpg" alt="Description of image">
Lists:

Unordered List:
html
Copy code
<ul>
  <li>Item 1</li>
  <li>Item 2</li>
</ul>
Ordered List:
html
Copy code
<ol>
  <li>First item</li>
  <li>Second item</li>
</ol>
Attributes
Common Attributes:
class: Assigns one or more class names to an element.
html
Copy code
<div class="container">Content</div>
id: Provides a unique identifier for an element.
html
Copy code
<p id="unique-paragraph">This paragraph is unique.</p>
src: Specifies the source URL for an image.
html
Copy code
<img src="image.jpg" alt="Description of image">
href: Specifies the URL of a link.
html
Copy code
<a href="https://example.com">Visit Example</a>
Unit 2: CSS Basics
CSS Overview
CSS (Cascading Style Sheets): Used to style and layout web pages.
CSS Syntax
Basic Syntax:
css
Copy code
selector {
  property: value;
}
Selectors
Type Selector:

css
Copy code
p {
  color: red;
}
Class Selector:

css
Copy code
.class-name {
  font-size: 20px;
}
ID Selector:

css
Copy code
#unique-id {
  margin: 10px;
}
Attribute Selector:

css
Copy code
[type="text"] {
  border: 1px solid #000;
}
Common Properties
Color:

css
Copy code
color: #333;
Font Size:

css
Copy code
font-size: 16px;
Margin and Padding:

css
Copy code
margin: 10px;
padding: 10px;
Background:

css
Copy code
background-color: #f0f0f0;
Unit 3: JavaScript Basics
JavaScript Overview
JavaScript: A scripting language used to create dynamic content on web pages.
JavaScript Syntax
Basic Syntax:
javascript
Copy code
// This is a single-line comment
var x = 5; // Variable declaration
console.log(x); // Output to console
Functions
Defining Functions:

javascript
Copy code
function greet(name) {
  return "Hello, " + name;
}
Calling Functions:

javascript
Copy code
console.log(greet("Alice"));
Events
Event Handling:
html
Copy code
<button onclick="alert('Button clicked!')">Click me</button>
Unit 4: AJAX and Fetch API
AJAX Overview
AJAX (Asynchronous JavaScript and XML): A technique for creating asynchronous web applications.
XMLHttpRequest
Basic Usage:
javascript
Copy code
var xhr = new XMLHttpRequest();
xhr.open('GET', 'https://api.example.com/data', true);
xhr.onload = function() {
  if (xhr.status >= 200 && xhr.status < 400) {
    console.log(xhr.responseText);
  }
};
xhr.send();
Fetch API
Basic Usage:
javascript
Copy code
fetch('https://api.example.com/data')
  .then(response => response.json())
  .then(data => console.log(data))
  .catch(error => console.error('Error:', error));
Unit 5: PHP Basics
PHP Overview
PHP (Hypertext Preprocessor): A server-side scripting language designed for web development.
PHP Syntax
Basic Syntax:
php
Copy code
<?php
echo "Hello, World!";
?>
Variables
Defining Variables:
php
Copy code
$name = "Alice";
echo $name;
Forms and Data Handling
Handling Form Data:
php
Copy code
if ($_SERVER["REQUEST_METHOD"] == "POST") {
  $name = $_POST['name'];
  echo "Hello, " . htmlspecialchars($name);
}
Unit 6: MySQL Basics
MySQL Overview
MySQL: A relational database management system used to store and manage data.
Connecting to MySQL
PHP Connection:
php
Copy code
$conn = new mysqli('localhost', 'username', 'password', 'database');
if ($conn->connect_error) {
  die("Connection failed: " . $conn->connect_error);
}
Querying MySQL
Basic Query:
php
Copy code
$result = $conn->query("SELECT * FROM users");
while ($row = $result->fetch_assoc()) {
  echo $row['username'];
}
Unit 7: Networking Basics
Networking Overview
Networking: The practice of connecting computers and other devices to share resources.
Network Types
LAN (Local Area Network): A network covering a small geographic area, like a home or office.
WAN (Wide Area Network): A network that spans a large geographic area, like the internet.
Networking Cables
Twisted Pair Cables:

STP (Shielded Twisted Pair): Provides protection against electromagnetic interference.
UTP (Unshielded Twisted Pair): Commonly used in networking, less resistant to interference.
Fiber Optic Cables: Use light to transmit data at high speeds over long distances.

IP Addressing and Subnetting
Subnetting: Dividing a network into smaller, manageable segments.

Example:

Subnet Mask for 5 Subnets: 255.255.255.224 provides 8 subnets with up to 30 hosts each.
