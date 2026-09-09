# QR Code Generator

A fast, lightweight, and responsive **QR Code Generator** built with **HTML5, CSS3, and Vanilla JavaScript**. Generate customized QR codes instantly from text or URLs, personalize their appearance, download them as PNG images, and manage recently generated QR codes directly in your browser.

## Features

* **Instant QR Generation**
  Generate QR codes instantly from text or web URLs.

* **Customizable QR Styles**
  Adjust QR code dimensions from **150px to 400px** and customize foreground and background colors.

* **High-Resolution Download**
  Download generated QR codes as high-quality PNG images.

* **QR Code History**
  Automatically save and retrieve recently generated QR codes using browser `localStorage`.

* **Dark & Light Mode**
  Switch between Dark and Light interface themes.

* **Clipboard Support**
  Easily copy input text or generated QR images to the clipboard.

* **Keyboard Support**
  Press **Enter** to generate a QR code quickly.

* **Responsive Design**
  Fully responsive interface that works across desktop, tablet, and mobile devices.

---

## Tech Stack

| Technology       | Purpose                                |
| ---------------- | -------------------------------------- |
| HTML5            | Application structure                  |
| CSS3             | Styling, responsive design, and themes |
| JavaScript       | Application logic and DOM manipulation |
| QR Code Library  | QR code generation                     |
| LocalStorage API | QR code history management             |
| Clipboard API    | Copy functionality                     |

---

## Project Structure

```text
qr-code-generator/
│
├── index.html          # Main HTML structure
├── style.css           # Styling and theme management
├── script.js           # Application logic and DOM manipulation
├── qrcode.min.js       # QR code generation library
└── README.md           # Project documentation
```

---

## Getting Started

### Prerequisites

No build tools, package managers, or backend server are required.

The application runs directly in any modern web browser.

### Installation

1. Clone the repository:

```bash
git clone https://github.com/YOUR_USERNAME/qr-code-generator.git
```

2. Navigate to the project directory:

```bash
cd qr-code-generator
```

3. Open `index.html` in your preferred web browser.

The application is ready to use.

---

## How It Works

1. Enter text or a URL into the input field.
2. Customize the QR code size if required.
3. Select foreground and background colors.
4. Generate the QR code.
5. Download the generated QR code as a PNG image.
6. Access previously generated QR codes from the history section.

---

## Core Functionality

### QR Code Generation

Converts user-provided text or URLs into scannable QR codes instantly.

### Customization

Users can customize:

* QR code dimensions
* Foreground color
* Background color

### History Management

Recently generated QR codes are stored locally using the browser's `localStorage` API, allowing users to access their previous QR codes without requiring a backend database.

### Theme Support

The application supports both Dark Mode and Light Mode for a better user experience.

### Clipboard Integration

Users can copy input content or generated QR images directly to the clipboard.

---

## Roadmap

Planned improvements include:

* [ ] Custom logo integration inside QR codes
* [ ] SVG export support
* [ ] PDF export support
* [ ] Wi-Fi QR code templates
* [ ] vCard/contact QR codes
* [ ] Multi-color gradient QR styling
* [ ] Additional QR code customization options

---

## Privacy

This application works entirely on the client side.

User input and QR code history are stored locally in the browser using `localStorage`. No backend server or external database is required for the core functionality.

---

## License

This project is open-source and available under the **MIT License**.

---

## Author

**Sivasurya**

Frontend Developer focused on building responsive and user-friendly web applications using modern web technologies.

---

If you find this project useful, consider giving it a star on GitHub.
