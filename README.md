# Facial Attendance System

## 📌 Overview
This project is a **Facial Recognition-Based Attendance System** built using **Python**, **OpenCV**, and **face-recognition**. It automates attendance marking by detecting and recognizing faces from a dataset of registered individuals.

## 🚀 Features
- Detects and recognizes faces using `face-recognition`.
- Registers new faces and encodes them for future recognition.
- Maintains an attendance record in a spreadsheet.
- Uses **Google Drive** integration for dataset storage.

## 🛠️ Setup Instructions

### 1️⃣ Install Dependencies
Ensure you have the required Python libraries installed:
```bash
pip install face-recognition opencv-python numpy pandas
```

### 2️⃣ Dataset Preparation
- Store known face images inside a `faces/` directory.
- Each image filename should be the person's name (e.g., `John_Doe.jpg`).

### 3️⃣ Run the Notebook
If using **Google Colab**, mount Google Drive first:
```python
from google.colab import drive
drive.mount('/content/Drive')
```
Then navigate to the appropriate working directory.

### 4️⃣ Encode Faces
Run the encoding function to process images and store facial encodings.

```python
faces = register_face()
encoded_faces = encode_faces(faces)
```

### 5️⃣ Detect & Recognize Faces
Execute the detection script to recognize and mark attendance.
```python
recognize_faces()
```

## 📊 Output
- The recognized faces are logged into an **Excel/CSV file** with timestamps.
- Unrecognized faces can be registered for future use.

## 📝 Notes
- Ensure the `faces/` directory is accessible.
- Images should be **clear and well-lit** for better recognition.

## 🤖 Technologies Used
- Python
- OpenCV
- Face Recognition API
- NumPy & Pandas

## 📬 Contact
For any queries, feel free to reach out!
- vaibhavuniyal10@gmail.com

