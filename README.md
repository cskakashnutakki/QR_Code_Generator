# QR Code Generator

A simple and responsive QR Code Generator web application built with HTML, CSS, and JavaScript. This tool allows users to generate QR codes for text or URLs instantly.

## Project Preview

## 1. Before Input
   <img width="958" height="508" alt="image" src="https://github.com/user-attachments/assets/984cdade-526c-47d9-a85a-d862e8545cb8" />

## 2. After Input
   <img width="960" height="508" alt="image" src="https://github.com/user-attachments/assets/94a6b029-85fd-42a6-a0e4-268ae5678f3a" />

## Features

- **Easy Input**: Enter any text or URL to generate a QR code.
- **Instant Generation**: Click the "Generate QR Code" button to create the QR code.
- **Responsive Design**: Works seamlessly on desktop and mobile devices.
- **Clean UI**: Dark theme with a gradient background for an appealing look.
- **Real-time Updates**: The QR code updates dynamically as you input new data.

## Technologies Used

- **HTML** ```Structure of the web page.```
- **CSS** ```Styling and responsive design.```
- **JavaScript** ```Logic for generating QR codes and handling user interactions.```
- **QR Server API** ```External API used to generate QR codes.```

## How to Use

1. Clone or download the project files.
2. Open `dist/index.html` in your web browser.
3. Enter the text or URL in the input field.
4. Click the "Generate QR Code" button.
5. The QR code will be displayed below the form.
6. To generate a new QR code, simply enter new text and click the button again.

## API Used

This project uses the [QR Server API](https://goqr.me/api/) to generate QR codes. The API endpoint is `https://api.qrserver.com/v1/create-qr-code/?size=200x200&data={data}`.

## Project Structure

```
Qr-Code-Generator/
├── dist/
│   ├── index.html
│   ├── style.css
│   └── script.js
└── README.md
```

## Contributing

Contributions are welcome! If you have suggestions or improvements, please create an issue or submit a pull request.
