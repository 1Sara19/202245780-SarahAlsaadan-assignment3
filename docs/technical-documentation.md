# Technical Documentation

## Project Overview

This project is a personal portfolio website developed using HTML, CSS, and JavaScript.
It was enhanced in Assignment 2 by adding dynamic features, data handling, and improved user interaction.

## Project Structure

- `index.html` → Defines the main structure and content of the website (About, Projects, Contact)
- `css/styles.css` → Handles styling, layout, themes, and responsive design
- `js/script.js` → Implements interactivity, dynamic content, and data handling
- `assets/images/` → Stores project images
- `docs/` → Contains documentation files (AI usage report and technical documentation)

## Features Implementation

### 1. Theme Toggle (Dark/Light Mode)

- Implemented using JavaScript and CSS variables
- The selected theme is saved using `localStorage`
- The theme is applied automatically when the page loads

### 2. Dynamic Greeting Message

- Displays a greeting based on the current time (morning, afternoon, evening)
- Implemented using JavaScript `Date` object
- Appears as a temporary notification on page load

### 3. Project Filtering

- Users can filter projects by category (All, Web, Database)
- Implemented using `data-*` attributes and event listeners
- Projects are shown/hidden dynamically without reloading the page

### 4. Contact Form Validation

- Validates user input (name, email, message)
- Uses regular expressions for email validation
- Displays success or error messages dynamically

### 5. User Feedback

- Error messages for invalid inputs
- Success message after form submission
- Message displayed when no projects match the selected filter

### 6. User Interaction

Users can interact with the interface by clicking filter buttons, submitting the contact form, and toggling between themes. The system provides immediate feedback to guide user actions.

## Design and Layout

- CSS Grid is used for the projects section layout
- Flexbox is used for navigation and controls
- Media queries ensure responsiveness across devices (mobile, tablet, desktop)

## Styling Approach

- Uses CSS variables for consistent theming (colors, backgrounds, borders)
- Smooth transitions are applied for better user experience
- Hover effects are used on buttons and project cards

## Responsiveness

- The layout adapts using media queries
- Grid switches to a single column on smaller screens
- Navigation adjusts for different screen sizes

## Data Handling

- `localStorage` is used to store user theme preference
- Form input is validated before processing
- Dynamic UI updates based on user interaction

## Conclusion

The project demonstrates the use of modern front-end development techniques including dynamic content updates, data handling, and user interaction improvements compared to Assignment 1.