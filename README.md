# OCR e-Bill Upload Application

This is a Progressive Web Application (PWA) for Optical Character Recognition (OCR) of e-bills. It allows users to upload e-bill PDFs and perform OCR on them.

## Features

- Upload e-bill PDF files
- Display a preview of the uploaded PDF
- Perform Optical Character Recognition (OCR) on the uploaded PDF
- Show upload status and error handling
- Responsive design for different screen sizes

## Technologies Used

- Frontend: React, Redux, react-pdf
- Backend: Node.js, Express, Multer, MongoDB
- OCR: Tesseract.js

## Project Structure

The project has the following structure:

ocr-app/
├── backend/
│ ├── controllers/
│ │ └── uploadController.js
│ ├── models/
│ │ └── File.js
│ ├── uploads/
│ ├── app.js
│ ├── package.json
│ └── ...
├── src/
│ ├── components/
│ │ ├── FileUploadForm.js
│ │ └── ...
│ ├── store/
│ │ ├── upload/
│ │ │ ├── uploadSlice.js
│ │ │ └── ...
│ │ └── ...
│ ├── App.js
│ ├── index.js
│ └── ...
├── public/
│ ├── index.html
│ ├── favicon.ico
│ └── ...
├── package.json
└── README.md


- The `backend` directory contains the server-side code, including controllers for file upload, models for MongoDB, and the main server file `app.js`.
- The `src` directory contains the frontend code, including components, Redux store setup, and the main application file `App.js`.
- The `public` directory contains static assets, including the HTML template and favicon.

## Installation and Usage

1. Clone the repository:

   
   git clone <repository-url>
# OCR e-Bill Upload Application

This is a Progressive Web Application (PWA) for Optical Character Recognition (OCR) of e-bills. It allows users to upload e-bill PDFs and perform OCR on them.

## Features

- Upload e-bill PDF files
- Display a preview of the uploaded PDF
- Perform Optical Character Recognition (OCR) on the uploaded PDF
- Show upload status and error handling
- Responsive design for different screen sizes


- The `backend` directory contains the server-side code, including controllers for file upload, models for MongoDB, and the main server file `app.js`.
- The `src` directory contains the frontend code, including components, Redux store setup, and the main application file `App.js`.
- The `public` directory contains static assets, including the HTML template and favicon.

## Installation and Usage

1. Clone the repository:

   ```bash
   git clone <repository-url>
2. Install dependencies for both the frontend and backend:
cd ocr-app
npm install
cd backend
npm install
3. Start the backend server:
cd backend
npm start
4. Start the frontend development server:
cd ocr-app
npm start
5. Open the application in your browser at http://localhost:3000.

## License
This project is licensed under the MIT License.
## Author
Kamender Singh Gangwar

Feel free to customize the content based on your specific project details.
