# Frontend Mentor - Product Preview Card Component Solution 🔗
This is my solution to the [Product Preview Card Component Solution challenge](https://) on Frontend Mentor.

## Overview ✨

### The Challenge

The goal was to build a responsive product preview card that matches the provided design for both desktop and mobile screens. Key requirements included:

- Building a responsive layout that adapts to different screen sizes.
- Implementing hover and focus states for the "Add to Cart" button.

### Preview

![Screenshot](./images/preview.jpg) 

## 🛠️ Technologies Used
- **HTML5** - For the semantic structure of the card.
- **CSS3** - For styling the component, including layout, typography, and hover states.
- **Flexbox** - Used for creating the main two-column layout and aligning items within each summary row.

## My Process 🛠️
### 1. HTML Structure 📋
I created a semantic HTML structure with:

- A single `<main>` container to wrap the entire card component for accessibility.
- A `<section>` or `<div>` for the main card, which I split into two child elements: one for the image and one for the text content.
- The text content included a heading (`<h1>`), a paragraph for the category, a description, and a `<div>` for the pricing details.
- A `<button>` element with a cart icon for the call-to-action.

### 2. Styling 🎨
- **Mobile-first approach** 📱
- **Typography** Imported and applied custom fonts
- **Layout**  I used Flexbox on the main container to easily arrange the two sections side by side on desktop. This also allows for a simple flex-direction: column change in the media query for mobile.
- **Pricing:** I used a Flexbox container for the price to align the discounted price and the original price horizontally. I also styled the discounted price with a specific color and bold weight and added a line-through to the original price.
- **Hover States:** I added a smooth transition to the background-color property of the button to create a subtle hover effect.

## 📚 What I Learned

- **Styling with Custom Fonts:** I practiced importing and applying custom fonts from a style guide, which is a common task in professional development.

- **Attention to Detail:** The biggest takeaway was the importance of adjusting small details like letter spacing, line height, and box-shadow values to make the final component look polished and match the design as closely as possible.


## 🔗 Links
- **🌐 Live Site URL**: [Product Preview Card Component Solution challenge](https://)

### **👥 Solved by M Olaya** 
<a href="https://www.linkedin.com/in/molaya">LinkedIn</a> 
