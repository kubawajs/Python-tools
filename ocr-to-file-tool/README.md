# OCR image to file python tool

Python tool for extracting text from images.

## Prerequisites

1. Tesseract-OCR

## Usage

```bash
python ./ocr-to-file-tool.py -i <image_name> -l <language_code> -o <output_file_name>
# only -i parameter is required
```

Available language codes for Tesseract-OCR - [click](https://github.com/tesseract-ocr/tesseract/blob/master/doc/tesseract.1.asc#languages-and-scripts)

## Libraries used

* pytesseract

## DONE

* image name as parameter
* language as parameter
* output name as parameter

## TODO

* pdf files support