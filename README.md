# Password Generator

This is a simple web-based password generator that allows users to generate random passwords with a combination of uppercase letters, lowercase letters, numbers, and symbols. The project is built using HTML, CSS, and JavaScript.

## Features

- **Random Password Generation:** Click the "Generate Password" button to create a random password with a specified length and a mix of character types.
- **Copy to Clipboard:** Easily copy the generated password to the clipboard by clicking the copy icon.

## How to Use

1. Open the `index.html` file in a web browser.
2. Click the "Generate Password" button to create a random password.
3. The generated password will be displayed in the input field.
4. Click the copy icon to copy the password to the clipboard.

## Project Structure

- **index.html:** The main HTML file that defines the structure of the web page.
- **style.css:** The stylesheet file containing the styling for the web page.
- **script.js:** The JavaScript file responsible for generating and copying passwords.

## Dependencies

- [Poppins](https://fonts.google.com/specimen/Poppins) font is used for styling. It is imported from Google Fonts.

## Customization

- You can customize the password length and character types by modifying the `length`, `uppercase`, `lowercase`, `numbers`, and `symbols` variables in the `script.js` file.

```javascript
const length = 12;
const uppercase = "ABCDEFGHIJKLMNOPQRSTUVWXYZ";
const lowercase = "abcdefghijklmnopqrstuvwxyz";
const numbers = "0123456789";
const symbols = "@#$%^&*()_+~|{}[]<>/-=";