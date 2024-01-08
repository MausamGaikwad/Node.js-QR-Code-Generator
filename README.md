# QR Code Generator

This is a simple command-line tool that allows you to generate QR codes for a given URL. It uses the 'inquirer' library for interactive prompts, 'qr-image' for QR code generation, and 'fs' for file system operations.

## Installation:

Make sure you have Node.js installed on your machine. You can install the project dependencies by running:

bash
npm install

## Usage:

To generate a QR code, run the following command:

``node index.js`

You will be prompted to enter a URL. After entering the URL, the tool will generate a QR code image ('qr_svg.png') and save the entered URL to a text file ('URL.txt').

## Dependencies:

- inquirer (https://www.npmjs.com/package/inquirer): Used for interactive command-line prompts.
- qr-image (https://www.npmjs.com/package/qr-image): Used for generating QR codes.
- fs (https://nodejs.org/api/fs.html): Node.js module for file system operations.

## Contributing:

Feel free to contribute to this project by opening issues or submitting pull requests.

## License:

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

### Please feel free to modify and customize it based on your specific project details. If you have any further questions or need additional help, let me know!
