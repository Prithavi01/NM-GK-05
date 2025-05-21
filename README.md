🛒 Shelf Product Detection using OpenCV
This project automatically detects missing products on a store shelf using image processing with OpenCV in Python. It visually marks missing slots and provides a row-wise summary of product presence.

📸 How it Works
Loads a shelf image (shop1.jpg)

Divides the image into a grid based on expected product placement (rows and columns)

Analyzes each cell to check if a product is present using contour detection

Highlights:

🟥 Red box for missing items

🟩 Green box for detected products

Outputs the total number of missing items per row

✅ Requirements
Python

OpenCV (cv2)

NumPy

Google Colab (optional, used for cv2_imshow)

🚀 How to Run
Upload your shelf image as shop1.jpg

Run the script in a Python environment (e.g., Google Colab or local Python)

The result will be displayed with annotations

🛠️ Configuration
You can modify these parameters in the script:

python
Copy
Edit
NUM_ROWS = 3
NUM_COLS = 5
CELL_WIDTH = 60
CELL_HEIGHT = 100
START_X = 50
START_Y = 80
ROW_SPACING = 130
COL_SPACING = 100
📂 Sample Output
The script prints missing item counts per row and displays an annotated image with red/green boxes
