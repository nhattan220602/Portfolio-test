# Portfolio Website

## Overview
Welcome to my personal portfolio website! This project showcases my skills in web development, with a focus on creating visually appealing and responsive designs using **HTML** and **CSS**. The portfolio highlights custom styling techniques, including image hover effects, gradient backgrounds, and responsive layouts, to demonstrate my ability to build modern, user-friendly web interfaces. This is a work-in-progress project, and I’m continuously adding new features and designs to enhance its functionality and aesthetics.

## Features
- **Custom CSS Styling**: 
  - Smooth background color gradients using `linear-gradient` and `radial-gradient`.
  - Image effects like hover overlays, filters (e.g., grayscale, blur), and `clip-path` for unique shapes.
  - Responsive image handling with `object-fit` and media queries.
- **Responsive Design**: Optimized for various screen sizes, ensuring a seamless experience on mobile and desktop devices.
- **Interactive Elements**: Hover effects and transitions for enhanced user engagement.
- **Accessibility**: Includes focus styles and descriptive `alt` text for images to ensure inclusivity.

## Demo
Visit the live demo: [Portfolio Website](https://nhattan220602.github.io/Portfolio-test)  
*Note*: If the live demo isn’t set up yet, follow the instructions below to view locally.

## Installation
To run this portfolio locally:
1. Clone the repository:
   ```bash
   git clone https://github.com/nhattan220602/Portfolio-test.git
2. Navigate to the project folder:
   ```bash
   cd Portfolio-test
3. Open index.html in a web browser (e.g., Chrome, Firefox) to view the portfolio. Alternatively, use a local development server:
   ```bash
   npx live-server

## Usage
To integrate these styles into your own project:

1. Link the styles.css file in your HTML:
   ```html
   <link rel="stylesheet" href="styles.css">
2. Apply the CSS classes to your elements. Example:
   ```css
   <div class="image-container">
    <img src="images/sample.jpg" alt="A sample image">
    <div class="overlay">View Details</div>
    </div>
3. Customize the styles in styles.css to match your design preferences.
     Portfolio-test/
├── images/               # Folder for images used in the portfolio
├── index.html           # Main HTML file for the portfolio
├── styles.css           # CSS file with custom styles
└── README.md            # This file
