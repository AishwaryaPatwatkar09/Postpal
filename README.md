# 📮 PostPal: Intelligent Address and Pincode Extractor

PostPal is a Python-based OCR project designed to automate the process of extracting addresses from scanned images and identifying valid Indian PIN codes using fuzzy matching.

## 🚀 Features

- 🧠 Optical Character Recognition (OCR) using Tesseract
- 🔍 Fuzzy matching of extracted text against a pincode dataset
- 📄 CSV support for reference postal data
- 🛠 Modular Python functions for image input, text extraction, and pincode matching

---

## 📂 Project Structure

postpal/
│
├── postpal.ipynb # Main notebook with OCR & matching logic
├── pincode.csv # Reference dataset of pincodes and areas
├── sample_images/ # (Optional) Folder for input address images
└── README.md # This file


---

## 📦 Requirements

- Python 3.x
- Libraries:
  - pandas
  - pytesseract
  - Pillow (PIL)
  - fuzzywuzzy
  - python-Levenshtein (optional for fuzzywuzzy speedup)

Install requirements:
```bash
pip install pandas pytesseract pillow fuzzywuzzy python-Levenshtein
