# QR Code Generator

A simple Node.js application that generates QR codes from URLs and saves them as images.

## Features

- Interactive command-line interface using Inquirer
- Generates QR code images from URLs
- Saves the original URL to a text file
- Uses modern ES modules

## Prerequisites

- Node.js (version 14 or higher)
- npm (Node Package Manager)

## Installation

1. Clone this repository:
```bash
git clone <your-repository-url>
```

2. Navigate to the project directory:
```bash
cd 2.4-qr-code-project
```

3. Install dependencies:
```bash
npm install
```

## Usage

1. Run the application:
```bash
node index.js
```

2. Enter the URL when prompted
3. The application will:
   - Generate a QR code image (`qr.png`)
   - Save the original URL to a text file (`url.txt`)

## Dependencies

- [inquirer](https://www.npmjs.com/package/inquirer) - For interactive command-line interface
- [qr-image](https://www.npmjs.com/package/qr-image) - For QR code generation

## Project Structure

- `index.js` - Main application file
- `qr.png` - Generated QR code image
- `url.txt` - Text file containing the original URL
- `package.json` - Project configuration and dependencies

## License

This project is licensed under the ISC License.

## Author

Sadeed Akhtar Khan Bibi
