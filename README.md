# Pixel to XLSX 🎨📊

A Python-based tool that extracts pixel color data from images and exports them directly into an Excel spreadsheet (.xlsx).

## Key Features
* Reads pixel data from images.
* Organizes data into a structured format using `pandas`.
* Generates formatted Excel files using `openpyxl`.

## Requirements
* Python 3.12+
* Dependencies: `pandas`, `openpyxl`, `Pillow`

## Usage 🚀

Follow these steps to convert your image to an Excel file:

1. **Prepare your image:**
   Place the image you want to process in the project folder (e.g., `input_image.png`).

2. **Configure the script:**
   Open `pixel.py` and ensure the input path matches your filename:
   ```python
   image_path = "input_image.png"
3. **Run the converter:**
    python pixel.py
4. **Get your results: Once the script finishes, a new file (e.g., pixel_data.xlsx) will appear in your directory. Each row in the spreadsheet represents a pixel with its R, G, B values and coordinates.**


## Structure
* pixel.py – Core script for image processing.

* env/ – Python virtual environment (ignored by Git).

* .gitignore – Configuration for ignoring unnecessary files.

* requirements.txt – List of required Python packages.
## Installation & Setup

1. **Clone the repository:**
   git clone [https://github.com/wavymejti/pixel-to-xlsx.git](https://github.com/wavymejti/pixel-to-xlsx.git)
   cd pixel-to-xlsx
2. **Create and activate a virtual environment:**
    python3 -m venv env
    # macOS/Linux:
    source env/bin/activate
    # Windows:
    .\env\Scripts\activate
3. **Install dependencies:**
    pip install -r "requierements.txt"
4. **Run the script**
    python pixel.py