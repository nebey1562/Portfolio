# Portfolio Website

## Overview

This is a personal portfolio website designed to showcase your skills, experience, and projects. The website includes a home page with an introduction, a navigation bar with a dark theme and logo, and a background image with a gradient overlay. The site is built using HTML, CSS, and Bootstrap 5, with custom styling and animations for a polished look.

## Features

- **Responsive Design**: The site is fully responsive, adjusting to different screen sizes and devices.
- **Dark Theme**: A modern dark theme is used for the overall look of the site.
- **Background Image**: The background features a gradient overlay to enhance visual appeal.
- **Animations**: Text content on the home page slides in for a dynamic presentation.
- **Custom Font**: Uses Google Fonts to improve typography.

## Files and Structure

- `index.html`: The main landing page of the portfolio.
- `nav.html`: Contains the HTML for the navigation bar (included via JavaScript fetch).
- `background.jpeg`: The background image for the site.
- `styles.css`: Custom CSS styles for the site (if applicable, otherwise styles are embedded in HTML).

## Usage of Bootstrap

Bootstrap is used to provide a responsive layout and pre-designed components for the website. Here's how Bootstrap was utilized:

1. **Navigation Bar**: 
   - The navigation bar uses Bootstrap's `navbar` component to create a responsive and collapsible menu. 
   - The `navbar-expand-lg` class ensures the menu collapses on smaller screens and expands on larger screens.
   - The `navbar-dark` and `bg-dark` classes are used to apply a dark theme to the navigation bar.

2. **Container and Grid System**:
   - The `container-fluid` class is used to create a full-width container for the navigation bar, ensuring it spans the entire width of the viewport.

3. **Buttons and Toggler**:
   - The `navbar-toggler` button is used to toggle the navigation menu on mobile devices, providing a user-friendly way to access menu items.

4. **Typography**:
   - Bootstrap's typography classes and grid system are used for consistent and responsive text sizing and alignment.

5. **Utility Classes**:
   - Various utility classes, such as `text-center` and `my-4`, are used for alignment and spacing.
