
![aee977ce-f946-4451-8b9e-bba278ba5f13](https://github.com/tonykalalian/qr-code-generator-nodejs/assets/120026287/dbfbb422-f4bd-4ac3-b1d6-efb202566103)

# QR Code Generator - Node.js

[![License](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![Node.js](https://img.shields.io/badge/Node.js-v18+-brightgreen.svg)](https://nodejs.org/)
[![npm](https://img.shields.io/badge/npm-v9+-orange.svg)](https://www.npmjs.com/)

## Description

The QR Code Generator is a versatile Node.js application that allows users to effortlessly create QR codes for their favorite images by simply providing a URL. The generator leverages the "inquirer" npm library to interact with users via a command-line interface, "qr-image" for producing QR codes, and "fs" to save the generated QR code as an image and store the provided URL in a text file.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Example](#example)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgments](#acknowledgments)

## Installation

1. Make sure you have [Node.js](https://nodejs.org/) (v14 or later) installed on your machine.
2. Clone this repository: `git clone <repository-url>`
3. Navigate to the project directory: `cd qr-code-generator-nodejs`
4. Install dependencies: `npm install`

## Usage

1. Run the application: `node index.js`
2. You will be prompted to enter the URL of the image you wish to encode.
3. After entering the URL, the application will generate a QR code image and save it as "qr_img.png" in the project directory.
4. Additionally, the provided URL will be saved in a text file named "URL.txt" for future reference.

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, feel free to open an issue or create a pull request. For major changes, please open an issue first to discuss the proposed changes.

## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgments

- The [inquirer](https://www.npmjs.com/package/inquirer) npm library for user interaction.
- The [qr-image](https://www.npmjs.com/package/qr-image) npm library for QR code generation.

---
Feel free to customize the repository name, description, and README file further to match your preferences and project specifics. Additionally, consider adding more sections to the README file, such as "Troubleshooting," "FAQs," "Support," etc., depending on the complexity and features of your application.
