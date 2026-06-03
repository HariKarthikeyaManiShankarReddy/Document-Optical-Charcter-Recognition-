# Document-Optical-Charcter-Recognition

An OCR-based receipt processing system using PaddleOCR and OpenCV that extracts bill details, dates, times, and purchased items from receipt images and exports structured JSON output.

# Optical Character Recognition (OCR) for Automated Receipt Processing

## Overview

This project is an OCR-based document processing system that automatically extracts and structures information from receipt images. The system leverages PaddleOCR and OpenCV to recognize text from scanned receipts and applies pattern-matching techniques to identify key information such as bill numbers, dates, times, and purchased items.

The project aims to reduce manual data entry efforts by converting unstructured receipt images into machine-readable JSON data.

## Features

* Image preprocessing using OpenCV for improved OCR accuracy.
* Text extraction using PaddleOCR.
* Adaptive thresholding and grayscale conversion for noise reduction.
* Automatic extraction of:

  * Receipt Date
  * Receipt Time
  * Bill/Invoice Number
  * Purchased Items
* Structured output generation in JSON format.
* Easy integration with invoice management and document automation systems.

## Technology Stack

* Python
* PaddleOCR
* OpenCV
* Regular Expressions (Regex)
* JSON

## Workflow

1. Load receipt image.
2. Preprocess image using grayscale conversion and adaptive thresholding.
3. Perform text recognition using PaddleOCR.
4. Extract relevant fields using regex-based pattern matching.
5. Generate structured JSON output containing receipt details.

## Project Structure

* Image Preprocessing Module
* OCR Text Extraction Module
* Information Extraction Module
* JSON Output Generator

## Sample Output

```json
{
  "date": "15/04/2026",
  "time": "14:32:10",
  "bill_number": "INV12345",
  "items": [
    "Milk 45.00",
    "Bread 30.00",
    "Eggs 60.00"
  ]
}
```

## Applications

* Invoice Processing
* Receipt Digitization
* Expense Management Systems
* Retail Automation
* Document Data Extraction

## Future Enhancements

* Support for multiple document formats.
* Handwritten text recognition.
* Multi-language OCR support.
* Integration with databases and cloud storage.
* Deep learning-based document classification.

This project demonstrates practical applications of Computer Vision, OCR, Image Processing, and Information Extraction techniques for real-world document automation tasks.

##Sources
chatgpt
youtube
Google Colab
