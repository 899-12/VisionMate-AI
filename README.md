# VisionMate - AI Powered Solution for Assisting Visually Impaired Individuals

**VisionMate** is an AI-powered application designed to assist visually impaired individuals by providing functionalities such as scene understanding, text extraction, text-to-speech conversion, and object detection.

---

## Features

1. **🖼️ Scene Understanding**  
   Generate a comprehensive scene description for visually impaired individuals, including object identification, scene context, and safety recommendations.

2. **📜 Text Extraction**  
   Extract text from images using Optical Character Recognition (OCR) technology.

3. **🎤 Text-to-Speech**  
   Convert extracted text into speech for auditory feedback.

4. **🔍 Object Detection**  
   Identify objects in images using YOLOv5 for enhanced awareness.

---

## Tech Stack

- **Programming Language:** Python
- **Libraries/Frameworks:**  
  - Streamlit (UI)
  - pytesseract (OCR)
  - pyttsx3 (Text-to-Speech)
  - torch and YOLOv5 (Object Detection)
  - google.generativeai and langchain_google_genai (Scene Understanding)

---

## Setup Instructions

### Prerequisites

1. Install [Tesseract-OCR](https://github.com/tesseract-ocr/tesseract) and configure the path:
   ```python
   pytesseract.pytesseract.tesseract_cmd = r'C:/Program Files/Tesseract-OCR/tesseract.exe'
2. Install the following Python libraries:
   ```python
   pip install streamlit pillow pytesseract pyttsx3 opencv-python torch ultralytics google-generativeai
   
### Usage
# Clone the repository:

```
git clone https://github.com/your-username/visionmate.git
cd visionmate
```
### Run the application:
```python
streamlit run app.py
```
#### Upload an image to use the following features:

-🖼️ Scene Description: Get a detailed description of the uploaded image.
-📜 Text Extraction: Extract and display text from the image.
-🎤 Text-to-Speech: Listen to the extracted text as speech.
-🔍 Object Detection: View objects detected in the image.
