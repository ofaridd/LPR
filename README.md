# License Plate Recognition (LPR)
This Project was aimed to Automatically recognize license plates using Neural Networks which is utilized using YOLOV8. Illustrated below is some images
prediction using YOLOV8 machine learning. For future implementations we will need to have a larger dataset, and increase iterations ‘epochs’ enhancing accuracy, and precision.

Each image produces a list of detected classes in a specific order and prints the boxes detected in the image, while also sorting them. The coordinates are referenced from the upper left corner.
Each row represents one detected class, with the x and y coordinates given in columns. For instance, the first row and first column represent the X coordinate of the box's center. While the
last 2 columns represent Width and Height of the box.
[Keep in mind this only works on Arabic Plates. I'm using a dataset has only Egyptian license plates.]

# Detecting Plates
![Real life example 1](https://github.com/user-attachments/assets/4a73a112-905a-4a40-b926-44136fe46253)

# Cropping Detected Plates
![first plate](https://github.com/user-attachments/assets/e5f01a09-c68c-42f5-a128-c0fc7144016e) ![second plate](https://github.com/user-attachments/assets/77340870-2743-4ebf-957b-f7ec1acca929)


# Recognize Letters/ numbers
![Plate one letters](https://github.com/user-attachments/assets/2a9f7fc8-cb9c-496f-a763-bfb83f8f823f) ![plate 2 letters](https://github.com/user-attachments/assets/e843bb99-52fa-4478-be15-b8ceb2148b92)

# Store detected classes
<img width="259" alt="Plate one OCR" src="https://github.com/user-attachments/assets/4db10ec7-e249-4f04-b6c9-f40c92ea5387"> <img width="170" alt="Plate two OCR" src="https://github.com/user-attachments/assets/5abfd332-51d3-4de8-969c-10502801ba9f">
