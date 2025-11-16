# QR Code Generator

A simple, single-file web application for generating QR codes. Just enter your desired text or URL, and get an instant QR code image.

## Features

*   **Instant Generation:** Quickly generate QR codes.
*   **Responsive Design:** Works well on various screen sizes, thanks to Tailwind CSS.
*   **Easy to Use:** Straightforward interface with a single input field and button.
*   **Single File:** All code (HTML, CSS, JavaScript) is contained within one `index.html` file, making it incredibly easy to deploy or share.

## Technologies Used

*   **HTML5:** For the basic structure of the web page.
*   **Tailwind CSS (via CDN):** For utility-first styling and responsive design.
*   **JavaScript:** For handling user input and QR code generation logic.
*   **QRious.js (via CDN):** A lightweight JavaScript library used for generating QR codes.

## How to Use

1.  **Open `index.html`:** Simply open the `index.html` file in any modern web browser.
2.  **Enter Text/URL:** Type or paste the text or URL you want to convert into a QR code into the input field.
3.  **Generate:** Click the "Generate QR Code" button or press `Enter` in the input field.
4.  **View & Save:** The QR code will appear below the input field. You can right-click (or long-press on mobile) on the generated QR code image to save it to your device.

## Local Development (Optional)

Since this is a single HTML file, you don't need a complex setup. You can just open the `index.html` file directly in your browser.

If you prefer to serve it via a local web server (e.g., for consistency or to avoid browser security warnings on some local file APIs, though not strictly necessary here):

1.  **Node.js:** If you have Node.js installed, navigate to the directory in your terminal and run `npx serve`.
2.  **Python:** If you have Python installed, navigate to the directory and run `python -m http.server`.

Then, open `http://localhost:8000` (or the port indicated by your server) in your browser.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.
