# Optical Character Recognition Test Project

This project demonstrates the use of Optical Character Recognition (OCR) to convert images of text into editable and searchable text. Leveraging the powerful Python library, PyTesseract, along with Pillow for image processing, we aim to showcase a simple yet effective approach to OCR.

Image example:

![ocr-readme](https://github.com/DevrMichael/ocr-test-project/assets/88589247/f7fedf3d-a781-48bb-a1f2-da6e8249d8b3)

Terminal output example:

![ocr-results](https://github.com/DevrMichael/ocr-test-project/assets/88589247/59c2ab98-1b29-4474-a828-719a66ebb0b9)

## Overview

OCR technology has widespread applications, from digitizing printed documents to automating data entry processes. This test project focuses on extracting text from images and presenting the basics of implementing an OCR system using Python.

## Features

- **Image to Text Conversion**: Convert images containing typed or handwritten text into machine-readable text.
- **Image Preprocessing**: Utilize Pillow for basic image processing to enhance OCR accuracy.
- **Configurable OCR Settings**: Customize PyTesseract's OCR engine settings to optimize text recognition for different types of images.

## Prerequisites

Before you begin, ensure you have met the following requirements:

- Python 3.6 or higher
- Pip for Python package management

## Installation

To set up the project environment:

1. Clone the repository:
```bash
git clone https://github.com/DevrMichael/ocr-test-project.git
```
3. Navigate to the project directory:
```bash
cd ocr-test-project
```
4. Install the required Python packages:
```bash
pip install Pillow pytesseract
```

## Usage

To run the OCR process on an image, follow these steps:

1. Ensure you have an image file (e.g., `ocr_image.png`) in the `data` directory.
2. Run the script `main.py`:
```bash
python3 main.py
```
3. The script will process the image and output the recognized text to the console.

## Configuration

The OCR settings can be adjusted by modifying the `myconfig` variable in `main.py`. Refer to the [PyTesseract documentation](https://pypi.org/project/pytesseract/) for more configuration options.

## Acknowledgments

- [PyTesseract](https://pypi.org/project/pytesseract/) for the OCR engine.
- [Pillow](https://python-pillow.org/) for image processing capabilities.

Thank you for checking out my OCR Test Project!
