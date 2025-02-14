

QR Code Generator Project
<img width="1680" alt="Screenshot 2025-02-14 at 11 57 21 PM" src="https://github.com/user-attachments/assets/2b52a487-102b-4e0c-ae54-1ae532d4a09b" />

<img width="378" alt="Screenshot 2025-02-14 at 11 58 28 PM" src="https://github.com/user-attachments/assets/3443cc85-8a7e-44b3-a0a3-a749b0c18c39" />


This is a QR Code Generator project built using Node.js, inspired by Angela Yu’s course. It allows users to generate QR codes from URLs using the inquirer and qrcode libraries.

Features
	•	Command-line interface using inquirer.
	•	Converts user-provided URLs into QR codes.
	•	Saves the generated QR codes as image files.

Technologies Used
	•	Node.js: JavaScript runtime.
	•	Inquirer.js: For interactive command-line prompts.
	•	qrcode: For generating QR codes.

Installation
	1.	Clone the repository:


	2.	Install dependencies:

npm install

Usage
	1.	Run the application:

node index.js


	2.	Enter the URL when prompted.
	3.	The QR code will be generated and saved as an image file.

Project Structure

|-- index.js       # Main project file
|-- package.json   # Project dependencies and scripts
|-- qr_img.png     # Output QR code image

Dependencies
	•	inquirer
	•	qrcode
