# Boxes_shape_color
Boxes Shape Color Generator
A dynamic DOM manipulation project that allows users to generate custom shapes (squares or circles) with specific colors and quantities. This project demonstrates fundamental concepts of JavaScript, event handling, and CSS styling.

🚀 Features
Dynamic Generation: Choose between a Square or Circle shape.

Customization: Select your preferred background color using a color picker.

Quantity Control: Specify the number of shapes to generate (up to 100).

Interactive Elements:

Single Click: Increment the number displayed inside the shape.

Double Click: Remove the individual shape from the container.

Visual Feedback: Hover effects on shapes with smooth scaling and shadows.

🛠 Technologies Used
HTML5

CSS3 (Flexbox, Transforms, Transitions)

Vanilla JavaScript (DOM Manipulation, Event Listeners)

📋 How to Use
Clone this repository or download the code.

Open index.html in any modern web browser.

Enter a number in the input field (Max: 100).

Select a shape from the dropdown menu.

Pick your desired color using the color input.

Click the "Add" button to render your shapes!

⚙️ How it Works
Event Listeners: The project uses a 'click' listener on the button to trigger the rendering loop and 'click'/'dblclick' listeners on each dynamically created element for interactivity.

DOM Manipulation: document.createElement is used to build the elements, and appendChild adds them to the main container.

Validation: A simple if statement ensures the user does not request more than 100 boxes at once, preventing potential browser performance issues.

Built as part of my Web Development coaching journey. 🚀
