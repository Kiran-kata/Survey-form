# Survey Form Project README

Link:: http://kiran-kata.github.io/Survey-form/

## Project Description

This project is a survey form created using HTML and CSS.  It's designed to gather user feedback and information. The form includes various input types, such as text fields, radio buttons, dropdown menus, and text areas. The styling is responsive, ensuring the form works well on different screen sizes.

## Files Included

*   The HTML file that structures the survey form.
*  The CSS file that styles the survey form.

## HTML Structure (`index.html`)

The Html file contains the following elements:

* A main container for the entire form.
* ** header:** Contains the survey title ("Survey Form") and a descriptive subtitle.
* ** form:** The form itself (`id="survey-form"`) with the following fields:
    * **Name:** A text input for the user's name (`required`).
    * **Email:** An email input for the user's email address (`required`).
    * **Age:** A number input for the user's age (optional, with constraints between 10 and 99).
    * **Gender:** Radio buttons for selecting gender (Male, Female, Other).  "Male" is the default.
    * **Where are you from?:** A dropdown select menu for the user's country.
    * **Which option best describes your current role?:** A dropdown select menu for the user's current role.
    * **Mention Other?:** A text area for users to specify their role if "Other" is selected.
    * **Would you recommend to a friend?:** Radio buttons for the recommendation question. "Definitely" is the default.
    * **What is your favorite feature?:** A dropdown select menu.
    * **What would you like to see improved?:** Checkboxes for selecting improvement areas.
    * **Any comments or suggestions?:** A text area for additional feedback.
    * **Submit:** A button to submit the form.

## CSS Styling (`form.css`)

The Css file provides the following styling:

* **Global Styles:** Resets box-sizing, sets font, and establishes a base for the page.
* **Background:** A gradient background with an image.
* **Form Container:** Styled container for the form, including padding, rounded corners, and a semi-transparent background.
* **Form Groups:** Spacing and layout for form elements.
* **Form Controls:** Styling for text inputs, selects, and text areas, including focus effects.
* **Radio Buttons/Checkboxes:** Custom styling for radio buttons and checkboxes.
* **Submit Button:** Styled submit button with a green background.
* **Responsive Design:** Media queries to ensure the form adapts to different screen sizes.

## How to Use

1.  **Open in a Browser:** Open the Html file in a web browser.
2.  **Fill in the Form:** Complete the form fields with the requested information.
3.  **Submit:** Click the "Submit" button.

    *(Note: This form is a front-end representation.  It does not include any back-end processing to store or handle the submitted data.)*

## Key Features

* **Responsive Design:** The form adapts to different screen sizes.
* **Styled Input Fields:** Custom-styled text inputs, dropdowns, radio buttons, checkboxes, and text areas.
* **Clear Structure:** Well-organized HTML with form groups and labels.
* **Optional Fields:** The age field is optional.
* **Required Fields:** Name, Email, Country and Current Role fields are required.

## Potential Improvements

* **Client-Side Validation:** Add JavaScript to validate form inputs before submission (e.g., check for valid email format, ensure required fields are filled).
* **Back-End Integration:** Implement a server-side script (e.g., using PHP, Python, Node.js) to process the form data and store it in a database or file.
* **Enhanced Styling:** Further refine the CSS for improved aesthetics and user experience (e.g., animations, transitions, custom error message styling).
* **Accessibility:** Ensure the form is fully accessible to users with disabilities (e.g., using ARIA attributes, providing alternative input methods).
* **JavaScript Enhancements:** Add features like auto-expanding text areas, dynamic field display based on user input, and interactive elements.
* **Error Handling:** Implement user-friendly error messages for invalid input.
* **Data Persistence:** Store form data (e.g., using local storage) to prevent data loss if the user accidentally refreshes the page.
* **Code Refactoring:** The radio button names are identical which can create problems during backend processing.
