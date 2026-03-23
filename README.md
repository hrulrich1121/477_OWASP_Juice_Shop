## Overview
This project is a basic login form built using HTML and JavaScript, inspired by the login system in OWASP Juice Shop. The goal of this project is to demonstrate fundamental front-end validation techniques and highlight the importance of secure input handling in web applications.

## Features
- Email and password input fields
- Client-side validation for empty fields
- Email format validation (must include "@")
- Password length validation (minimum 8 characters)
- JavaScript event handling for form submission

## Implementation Details
The login form is implemented using a simple HTML structure with a form element containing two input fields: email and password. JavaScript is used to add an event listener to the form submission. When the user submits the form, validation checks are performed to ensure the email contains "@" and the password is at least 8 characters long. If validation fails, form submission is prevented and an alert is displayed to the user.

## Security Considerations
This project demonstrates only client-side validation. In a real-world application, server-side validation must also be implemented to ensure security. Client-side validation alone is not sufficient to prevent attacks such as SQL Injection or authentication bypass.
