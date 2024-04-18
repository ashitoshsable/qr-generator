# QR Code Generator

Welcome to the QR Code Generator repository! This simple Node.js application takes a URL input from the user and generates a corresponding QR code image. It also saves the user input to a text file for future reference.

## Features

- **User-friendly Interface:** Utilizes the inquirer npm package to provide a seamless user experience for inputting URLs.
- **QR Code Generation:** Uses the qr-image npm package to transform the user-entered URL into a QR code image.
- **Data Persistence:** Saves the user input to a text file using the native fs module for easy retrieval.

## Installation

1. Clone this repository to your local machine.
2. Navigate to the project directory.
3. Run `npm install` to install the necessary dependencies.

## Usage

1. Open a terminal and navigate to the project directory.
2. Run `node index.js` to start the application.
3. Follow the prompts to enter your URL.
4. Once entered, a QR code image will be generated and saved as `my_png.png`.
5. The entered URL will also be saved in `inputs.txt`.

## Requirements

- Node.js
- npm (Node Package Manager)

## Dependencies

- [inquirer](https://www.npmjs.com/package/inquirer): Interactive CLI prompts for user input.
- [qr-image](https://www.npmjs.com/package/qr-image): Library to generate QR codes.
- [fs](https://nodejs.org/api/fs.html): Node.js file system module for file operations.

## Contributing

Contributions are welcome! Feel free to fork this repository and submit pull requests for any enhancements or bug fixes.

