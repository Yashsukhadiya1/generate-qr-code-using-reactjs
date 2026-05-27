# QR Code Generator

A React.js app that generates custom QR codes from any text or URL — with download and copy support.

> Developed by Yash Sukhadiya

## Screenshots

![App Preview](screenshot.png)
![Sample QR Code](qrcode-sample.png)

## How to Run

Make sure you have **Node.js** installed on your machine.

1. Clone the repository:

```bash
git clone https://github.com/thamerh/generate-qr-code-using-reactjs.git
```

2. Navigate to the project folder:

```bash
cd generate-qr-code-using-reactjs
```

3. Install dependencies:

```bash
npm install
```

4. Start the development server:

```bash
npm start
```

5. Open your browser and go to `http://localhost:3000`

## Usage

1. Enter any text or URL in the input field.
2. The QR code is generated instantly on the right.
3. Click **Download** to save the QR code as a PNG file.
4. Click **Copy** to copy the QR code image to your clipboard.

## Features

- Instant QR code generation from text or URLs
- Download QR code as PNG
- Copy QR code to clipboard
- Clean, minimal UI

## Tech Stack

- React.js 18
- qrcode.react
- html2canvas
- react-icons

## Acknowledgements

- [qrcode.react](https://www.npmjs.com/package/qrcode.react)
- [html2canvas](https://www.npmjs.com/package/html2canvas)
