# QR Code Generator

A simple and intuitive QR Code Generator built with HTML, CSS, and JavaScript.

## Features
- Generate QR codes from text or URLs.
- Responsive design for various screen sizes.
- Real-time QR code generation.
- User-friendly interface.

## Installation
1. Clone the repository:
    ```sh
    git clone https://github.com/yourusername/qrcode-generator.git
    ```
2. Navigate to the project directory:
    ```sh
    cd qrcode-generator
    ```

## Usage
1. Open `index.html` in your web browser.
2. Enter text or a URL in the input field.
3. Click the "Generate QR Code" button to generate and display the QR code.
4. The QR code will be dynamically generated and displayed below the input field.

## Technologies Used
- HTML: For structuring the web page.
- CSS: For styling the web page.
- JavaScript: For adding interactivity and generating QR codes.

## How It Works
- The user inputs text or a URL into the input field.
- When the "Generate QR Code" button is clicked, the JavaScript function triggers an API call to `https://api.qrserver.com/v1/create-qr-code/` with the input data.
- The API returns a QR code image, which is then displayed on the web page.
