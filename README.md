# dom-project-2
# Color Changer

This is a simple web application that allows users to change the color of a box interactively by pressing a button. The project is built using HTML, CSS, and JavaScript.

## Features

- Displays a heading "Color Changer".
- A box that changes color when the "Change Color" button is clicked.
- Generates random colors in a hexadecimal format.

## Project Structure

The project consists of three main files:

- `index.html`: The HTML file that sets up the structure of the web page.
- `styles.css`: The CSS file that styles the web page elements.
- `script.js`: The JavaScript file that adds interactivity to the button and color box.

## Getting Started

### Prerequisites

- A web browser (Chrome, Firefox, Safari, etc.) to view the application.

### How to Run the Application

1. Clone or download the repository.
2. Open the `index.html` file in your web browser.
3. Click on the "Change Color" button to see the color of the box change dynamically.

## Code Explanation

- **HTML**:
  - A `div` with the class `container` holds the title, color box, and button.
  - The button has the ID `change-color-btn`, and the box has the ID `color-box`.

- **CSS**:
  - Styles the container to center the content, gives the color box a default size and color, and styles the button.

- **JavaScript**:
  - Listens for the DOMContentLoaded event.
  - Defines the `getRandomColor()` function to generate a random hexadecimal color.
  - Adds an event listener to the button that changes the color of the box when clicked.

## Authors

- Nnamuzie Prince-Praise Munachi
