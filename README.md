# Word Art with Python

This project generates a visually appealing word art using Python. It combines a word cloud shaped in a specific design with a custom background image for an engaging and creative output. The project is designed using Python libraries like `wordcloud`, `matplotlib`, `pandas`, `numpy`, and `Pillow`.

---

## Features

- Generates word art in a specific shape defined by a mask image (`mariam.png`).
- Reads text data for the word cloud from a CSV file (`text.csv`).
- Displays the word cloud over a background image (`background.jpg`).
- Uses customizable parameters like word cloud dimensions and transparency.

---

## File Descriptions

### 1. `main.py`
- Main Python script for generating the word art.
- Reads text data from `text.csv` and generates the word cloud based on the design in `mariam.png`.
- Overlays the word cloud on `background.jpg` with an alpha blending effect for smooth integration.

### 2. `mariam.png`
- A mask image defining the shape of the word cloud.
- The text in the word cloud will take the shape defined by this image.

### 3. `background.jpg`
- The background image over which the word cloud is displayed.
- Provides a visually rich backdrop for the word art.

### 4. `text.csv`
- A CSV file containing the text data for the word cloud.
- Each row should include a column named `text` with the words or phrases to be used in the word cloud.

---

## Prerequisites

Before running the script, ensure you have the following installed:
- Python 3.6 or later
- Required libraries: `wordcloud`, `pandas`, `matplotlib`, `numpy`, `Pillow`

You can install the required libraries using:
```bash
pip install wordcloud pandas matplotlib numpy pillow
