# Registration Form 
#### learned it from [freeCodeCamp](https://www.freecodecamp.org/) || See it Live at [CodePen](https://codepen.io/shady-ashraf/pen/ExqzxxN)
###### You can use HTML forms to collect information from people who visit your webpage. In this course, you'll learn HTML forms by building a signup page. You'll learn how to control what types of data people can type into your form, and some new CSS tools for styling your page.
---

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [File Structure](#file-structure)
- [HTML Details](#html-details)
- [CSS Styling](#css-styling)
- [Deployment](#deployment)
- [Selectors Used in the Project](#Selectors-Used-in-the-Project)

---

## Overview
The **Registration Form** allows users to provide their personal information for account creation. It includes interactive and required fields, styled for readability and ease of use.

**Technologies used:**
- HTML5
- CSS3

**Live Preview:**  
The form submits data to `https://register-demo.freecodecamp.org`.

---

## Features
- User-friendly layout with a responsive design.
- Validation for required fields and specific input patterns.
- Input types include text, email, password, radio buttons, file upload, number, dropdown, and textarea.
- Ensures users agree to terms and conditions via a required checkbox.
- Minimalist design with a dark theme for readability.

---

## File Structure
```
project/
├── index.html  # Main HTML file containing the registration form
└── styles.css  # CSS file for styling the form and page
```

---

## HTML Details
The HTML file (`index.html`) defines the form structure and includes:
- **Form Elements:**
  - Text inputs for first and last names, email, and password.
  - Radio buttons to select account type (personal or business).
  - File input for uploading a profile picture.
  - Dropdown to choose how users heard about the service.
  - Textarea for bio submission.
  - Checkbox for terms and conditions.
- **Validation Rules:**
  - All fields except optional ones (e.g., profile picture) require valid input.
  - Password must be 8+ characters and match the `[a-z0-5]` pattern.

---

## CSS Styling
The CSS file (`styles.css`) provides a modern, responsive design:
- **Theme:** A dark background (`#1b1b32`) with light text (`#f5f6f7`).
- **Form Styling:**
  - Responsive width: 60% of viewport with a max of 500px and min of 300px.
  - Fieldsets separated by a 3px solid line for clarity.
  - Interactive inputs styled with `#0a0a23` background and white borders.
- **Button Design:**  
  The submit button is styled to stand out with a width of 60% and contrasting colors.

---

## Deployment
1. Clone the repository:
   ```bash
   git clone https://github.com/shadyashraf174/Registration-Form
   ```
2. Open the `index.html` file in any web browser.

---

## Selectors Used in the Project


### **Selectors in HTML**

#### **Element Selectors**
- **`<body>`**: Defines the main container for the entire page.
- **`<h1>` and `<p>`**: Used for the form heading and introductory text.
- **`<form>`**: Encapsulates all the input elements and organizes the form structure.
- **`<fieldset>`**: Groups related inputs for styling and semantic clarity.
- **`<label>`**: Associates labels with input fields using the `for` attribute.
- **`<input>`**: Collects user input, with types such as:
  - `text`
  - `email`
  - `password`
  - `radio`
  - `file`
  - `checkbox`
  - `number`
  - `submit`
- **`<textarea>`**: Provides a multi-line text input area.
- **`<select>` and `<option>`**: Creates a dropdown menu for multiple choices.
- **`<a>`**: Hyperlinks the "terms and conditions."

#### **Attributes Used**
- `id`: Assigns unique identifiers for elements (e.g., `id="first-name"`).
- `class`: Groups elements for styling (e.g., `class="inline"`).
- `required`: Marks fields as mandatory.
- `pattern`: Defines a regex pattern for input validation.
- `min` and `max`: Restricts numerical input ranges.

---

### **Selectors in CSS**

#### **Element Selectors**
- **`body`**: Styles the overall page (e.g., background color, font size).
- **`h1`, `p`**: Centers the text and adjusts margins.
- **`form`**: Sets the width, max-width, and padding of the form container.
- **`fieldset`**: Adds padding and border styling to grouped input fields.
- **`label`**: Adds spacing between labels and input fields.
- **`input`, `textarea`, `select`**: Styles the interactive elements with consistent dimensions and colors.
- **`a`**: Colors hyperlinks for visibility.

#### **Class Selectors**
- **`.inline`**: Styles elements to align horizontally (e.g., radio buttons and checkboxes).

#### **Attribute Selectors**
- **`input[type="submit"]`**: Specifically targets the submit button for unique styling.
- **`input[type="file"]`**: Styles the file upload input.

#### **Pseudo-Class Selectors**
- **`fieldset:last-of-type`**: Removes the bottom border from the last fieldset.

---

### Summary of Usage
1. **Element Selectors:** Used for general, broad styling (e.g., body, form, and input elements).
2. **Class Selectors:** Applied for specific styling requirements, such as inline alignment.
3. **Attribute Selectors:** Target specific input types (e.g., submit and file inputs) for specialized styling.
4. **Pseudo-Class Selectors:** Enhance usability with conditional styling for the last fieldset. 

---

![image](https://github.com/user-attachments/assets/6af3917d-ad89-4354-94e2-bb9c906dc94f)

---
