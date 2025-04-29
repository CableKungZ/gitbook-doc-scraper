# Documentation Scraper (PancakeSwap or Any Doc Site)

This Python script scrapes documentation from [PancakeSwap](https://docs.pancakeswap.finance/) or any similarly structured documentation website, and compiles the content (including text and images) into a `.docx` Word document.

## 📌 Features

- Crawls all internal pages within a documentation website
- Extracts headings, paragraphs, lists, and images from `<main>` content
- Saves images locally and embeds them into a Word document
- Outputs a structured `.docx` file for offline reading or archiving

## 📁 Output

- `output_document.docx` – The compiled document
- `downloaded_images/` – Folder containing all downloaded images

## 🚀 How to Use

1.Clone the repository:
   ```bash
   git clone https://github.com/CableKungZ/gitbook-doc-scraper.git
   cd pancakeswap-doc-scraper
   ```

2.Install required libraries:
  ```bash
  pip install -r requirements.txt
  ```
3.Run the script: 
  ```bash
  python scraper.py
  ```
⚠️ Note: This script respects basic rate limiting by sleeping 0.5 seconds between requests.

## 📦 Requirements
All dependencies are listed in requirements.txt.

## 📜 License
MIT License – feel free to use, share, and modify.


