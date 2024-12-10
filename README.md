# Resume Image Parser

This project is an image parser that extracts structured data from your resume (PDF format) by converting it into an image and using OCR (Optical Character Recognition) to extract text. The text is then organized into categories such as "Introduction", "Education", "Experience", and "Projects", enabling easy parsing and extraction of meaningful information.

## Features
- Converts resume (PDF) to images.
- Uses Tesseract OCR to extract text from images.
- Preprocesses the image for better text recognition (adaptive thresholding, resizing).
- Extracts and organizes the text into structured sections.
- Provides clear separation between different sections like Education, Experience, and Projects.

## Installation

### Prerequisites

- Python 3.7+ is required.
- `pip` to install dependencies.

### Dependencies
- The project uses the following Python packages:

- pdf2image: For converting PDF pages to images.
- pytesseract: For OCR text extraction from images.
- opencv-python: For image preprocessing.
- matplotlib: For visualizing images.
- Pillow: For image handling.
- numpy: For numerical operations.
