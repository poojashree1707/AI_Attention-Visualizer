### AI Attention Visualizer

#### AI Attention Visualizer is a Streamlit-based application that demonstrates how attention can be calculated and visualized from text extracted from an uploaded image.

#### The application uses OCR to extract text from an image, generates word embeddings using Sentence Transformers, calculates attention scores, and displays the attention values using a visual interface.

### Features

* Upload an image containing text
* Extract text using OCR
* Clean and process the extracted text
* Generate word embeddings using Sentence Transformers
* Calculate attention scores
* Visualize attention values for individual words
* Interactive Streamlit interface

### Project Structure
#### AI-Attention-Visualizer


├── app.py

├── attention.py

├── embedding.py

├── ocr.py

├── requirements.txt

└── README.md

### How It Works

### 1. Image Upload

#### The user uploads an image containing text through the Streamlit interface.

<img width="425" height="634" alt="Screenshot 2026-09-29 150507" src="https://github.com/user-attachments/assets/c4729d65-1616-4f43-8f6b-64e7361993dd" />

### 2. OCR Text Extraction

#### Pytesseract and Tesseract OCR are used to extract text from the uploaded image.

### 3. Text Processing

#### The extracted text is cleaned and divided into individual words for further processing.

### 4. Embedding Generation

#### Sentence Transformers with the all-MiniLM-L6-v2 model is used to generate numerical representations of the words.

### 5. Attention Calculation

#### Query, Key, and Value representations are generated and used to calculate attention scores using NumPy.

### 6. Visualization

#### The calculated attention scores are displayed in the Streamlit application to show the relative attention assigned to different words.

<img width="849" height="654" alt="Screenshot 2026-09-29 150626" src="https://github.com/user-attachments/assets/7f86ae86-c77b-4264-8eb5-afcbd04235d8" />

<img width="811" height="830" alt="Screenshot 2026-09-29 150644" src="https://github.com/user-attachments/assets/21e9acac-a089-4ae0-b3cf-6d6b5b5f8229" />

<img width="750" height="712" alt="Screenshot 2026-09-29 150707" src="https://github.com/user-attachments/assets/13baa954-18e9-4fcc-a688-d7a1a02c9bd0" />

### You can now view my Streamlit app in your browser.

  Local URL: http://localhost:8501

  
  Network URL: http://10.233.0.59:8501

  
