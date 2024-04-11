# QRcode-generator
This web-based tool creates QR codes for provided URLs, utilizing a stack comprising HTML, CSS, JavaScript, Node.js, and Express.js. Users can input any URL, triggering the server to convert it into a scannable QR code using the qrcode library. The application's interface is designed for responsiveness across devices, ensuring usability on desktops and mobile platforms alike. By combining these technologies, the app offers a streamlined solution for generating QR codes, enhancing accessibility and facilitating information sharing in various contexts, from marketing campaigns to personal use scenarios.
# Features
- Generates QR codes for URLs entered by the user.
- Simple and easy-to-use interface.
- Responsive design for various screen sizes.
# Folder Structure
- public/: Contains CSS.
   - style.css: CSS styles for the application.
- views/:
   - index.ejs: templating engine to render HTML file with the user interface.
- index.js: Main server file with Express.js setup and logic for generating QR codes using the qrcode package.
- package.json: Node.js project configuration file.
- README.md: Documentation file (you're reading it right now).
# Prerequisites
Before running the application, ensure you have the following installed:
- Node.js (https://nodejs.org/)
- npm (Node Package Manager, comes with Node.js)
# Dependencies
- Express.js: Web framework for Node.js.
- EJS: Templating engine for rendering HTML pages.
- qrcode: Library for generating QR codes.
- qr-image: for displayong the generated QR codes.
# Getting Started
1. Clone this repository to your local machine: https://github.com/Sahilbal/qrcode-generator.git
2. Navigate to the project directory: cd qr-generator
3. Install dependencies: npm install
4. Start the server: node index.js
5. Open your browser and go to http://localhost:3000 to access the QR code generator web app.
# Contributions
Contributions are welcome! Feel free to fork the repository and submit pull requests for any improvements or additional features.
