# QR Code Generator

This web application allows users to generate QR codes dynamically based on the input provided.

## Features

- Generate QR codes for any text input.
- Customize the size and background color of the QR codes.

## Technologies Used

- HTML
- CSS
- JavaScript
- React.js

## QR Code Generation API

This application utilizes the QR code generation API provided by [qrserver.com](http://api.qrserver.com/v1/create-qr-code/). It generates QR codes using the following URL format:
Where:
- `${word}` is the data to be encoded into the QR code.
- `${size}` is the size of the QR code.
- `${bgColor}` is the background color of the QR code.

## Usage

1. Clone the repository.
2. Install dependencies using `npm install`.
3. Start the development server using `npm start`.
4. Open the web application in your browser.

## Contributing

Contributions are welcome! Feel free to open an issue or submit a pull request.
