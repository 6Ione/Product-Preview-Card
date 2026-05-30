# To-DO List
1. Fix mobile and desktop viewports
* Fix how the image is displayed, it breaks in different sizes
* Styling breaks on different mobile viewports

2. Ensure code works and styling displays properly.

======================================
# Error list:
* <button> is missing required "type" attribute
* <button class="add-to-cart">Add to Cart</button>

# Syntax & Validation:
* Use only recognized property values to ensure styles apply correctly and consistently.
* font-weight: 500, 700

# Accessibility:
* Provide alternatives for users who prefer reduced motion to prevent motion sickness and other accessibility issues.
* transition: background-color 0.3s ease

* Use em or rem units in media queries to respect user font-size preferences and ensure better accessibility.

* @media (max-width: 600px) {
      body{
        background-color: hsl(30, 38%, 92%)

# Responsive Design
* Consider using relative units (em, rem) instead of absolute units (px, pt) to support resizing and improve accessibility.
* max-width: 400px

# Best Practice
* Use logical properties (e.g., inline-start instead of left) to support different reading directions and improve internationalization.
* margin-bottom: 20px

* Consider using CSS functions like calc(), min(), and clamp() to create more responsive and flexible layouts that adapt to different viewport sizes.
* font-size: 0.6875rem

* Use CSS custom properties (variables) to centralize values, improve consistency, and make site-wide changes easier to implement.
* color: hsl(228, 45%, 44%)

* Consider using min-width instead of max-width and using a mobile-first approach, which can lead to cleaner code and better performance on smaller devices.

* @media (max-width: 600px) {
      body{
        background-color: hsl(30, 38%, 92%)