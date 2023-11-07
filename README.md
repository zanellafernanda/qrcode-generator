# QR Code Generator using Node.js

This is a simple QR code generator application built with Node.js. It allows you to input a URL and generate a QR code image for that URL.

## Pre-requisites

Before using this application, make sure you have the following installed:

- Node.js: You can download and install Node.js from [nodejs.org](https://nodejs.org/).

## Installation

1. Clone this repository to your local machine:

```bash
git clone https://github.com/zanellafernanda/qrcode-generator.git
```

2.  Change to the project directory:

```bash
cd qr-code-generator-nodejs
```
3.  Install the required dependencies:

```bash
npm install
```
## Usage

1.  Run the application by executing the following command in your terminal:

```bash
node index.js
```
2.  You will be prompted to enter a URL. Type in the URL and press Enter.
    
3.  The application will generate a QR code image (qr-img.png) containing the URL you provided.
    
4.  Additionally, the entered URL will be saved in a text file (URL.txt).
    
5.  You can find the generated QR code image and the URL text file in the project directory.
    

## Dependencies

-   [inquirer](https://www.npmjs.com/package/inquirer): Used for prompting the user to enter the URL.
-   [qr-image](https://www.npmjs.com/package/qr-image): Used for generating QR code images.
-   [fs](https://nodejs.org/api/fs.html): Node.js built-in module for file system operations.

## Author

-   Fernanda Zanella Alves