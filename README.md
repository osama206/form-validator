# Form Validator

## Description
This is a simple form validator web application built using HTML, CSS, and JavaScript. It provides basic validation for user registration forms including fields for full name, phone number, email address, website URL, and password.

## Features
- Validates input fields for required information.
- Checks if passwords match.
- Provides visual feedback for valid and invalid inputs.
- Displays error/success messages.

## Getting Started
To get started with this project, follow these steps:

1. Clone the repository to your local machine:
    ```
    git clone https://github.com/osama206/form-validator.git
    ```

2. Navigate to the project directory:
    ```
    cd form-validator
    ```

## Usage
Simply open the `index.html` file in your web browser to use the form validator. Fill out the required fields and submit the form to see the validation in action.

## Demo
A live demo of this project is available on GitHub Pages: [Form Validator Demo](https://osama206.github.io/form-validator/)

## Files Included
- `index.html`: Contains the HTML structure of the form validator.
- `style.css`: Stylesheet for the HTML elements.
- `script.js`: JavaScript file for form validation logic.

## Credits

### Fonts:

- [Google Fonts](https://fonts.google.com)
  - Google Fonts was used to import and apply custom fonts to the form validator, enhancing the visual appeal of the web application.

### Documentation:

- [MDN Web Docs: `<input>` element](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/input)
  - This documentation was referenced to understand the various attributes and types of the `<input>` element, helping in implementing input fields for user data.
  
- [W3Schools: HTML Forms](https://www.w3schools.com/html/html_forms.asp)
  - This resource provided guidance on creating HTML forms, ensuring proper structure and attributes for form elements.
  
- [MDN Web Docs: `:valid` pseudo-class](https://developer.mozilla.org/en-US/docs/Web/CSS/:valid)
  - The `:valid` pseudo-class documentation was utilized to style input fields based on their validity, providing visual feedback to users.
  
- [MDN Web Docs: Constraint Validation](https://developer.mozilla.org/en-US/docs/Web/Guide/HTML/HTML5/Constraint_validation)
  - This resource explained the HTML5 constraint validation API, which was employed to validate form inputs without the need for custom JavaScript validation logic.
  
- [MDN Web Docs: Form Validation](https://developer.mozilla.org/en-US/docs/Learn/Forms/Form_validation)
  - Understanding form validation techniques from this documentation assisted in implementing robust client-side validation for the form validator.
  
- [HTML.com: Input Pattern](https://html.com/attributes/input-pattern/)
  - The input pattern documentation provided insights into using regular expressions to define input patterns, ensuring data entered by users met specific criteria.
  
- [Regexr: Regular Expression Tester](https://regexr.com/3bfsi)
  - Regexr was used to test and refine regular expressions for input patterns, ensuring accurate validation of user input.
  
- [MDN Web Docs: HTMLFormElement.submit event](https://developer.mozilla.org/en-US/docs/Web/API/HTMLFormElement/submit_event)
  - Information from this documentation helped in implementing event handling for form submission, allowing validation logic to be executed before form submission.
  
- [W3Schools: Event preventDefault() Method](https://www.w3schools.com/jsref/event_preventdefault.asp)
  - Understanding the `preventDefault()` method from W3Schools enabled preventing the default form submission behavior, allowing custom validation logic to be applied before submission.
  
- [CSS-Tricks: Form Validation Part 1: Constraint Validation in HTML](https://css-tricks.com/form-validation-part-1-constraint-validation-html/)
  - This article provided detailed insights into HTML constraint validation, guiding the implementation of validation rules directly in HTML without the need for JavaScript.

- [Rangle.io: How to Store User Passwords and Overcome Security Threats in 2017](https://rangle.io/blog/how-to-store-user-passwords-and-overcome-security-threats-in-2017)
  - This article from Rangle.io provides insights into secure password storage techniques and strategies to mitigate security threats, which informed the implementation of password validation in the form validator application.

These resources were invaluable in understanding HTML form elements, CSS styling, JavaScript event handling, and form validation techniques, which were essential in building the Form Validator application.
