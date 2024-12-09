# Vision AI Companion 👁️🖋️🔊

## Overview
Vision AI Companion is an advanced Streamlit-based application that provides visually impaired individuals with access to image descriptions, text extraction, and text-to-speech functionalities. It leverages the power of Google Generative AI and Tesseract OCR for scene understanding and text recognition. The application is also integrated with a Text-to-Speech engine to convert the extracted text into spoken words.

## Features
- **Describe Scene**: Get AI insights about the image, including objects and suggestions.
- **Extract Text**: Extract visible text using OCR from the uploaded image.
- **Text-to-Speech**: Hear the extracted text aloud using a text-to-speech engine.

  ## ![Sample Image](C:\Users\kadir\OneDrive\Pictures\Screenshots\Screenshot%202024-12-09%20231208.png)

## How It Works
1. **Upload an Image**: Drag and drop or browse an image in JPG, JPEG, or PNG format.
2. **Choose a Feature**:
   - **Describe Scene**: Generates a scene description using Google Generative AI.
   - **Extract Text**: Uses Tesseract OCR to extract text from the image.
   - **Text-to-Speech**: Converts the extracted text to speech using pyttsx3.
3. **View Results**: View the scene description, extracted text, or listen to the text through text-to-speech.

## Technologies Used
- **Streamlit**: For building the user interface.
- **PIL**: For image processing.
- **Tesseract OCR**: For text extraction from images.
- **pyttsx3**: For text-to-speech functionality.
- **Google Generative AI**: For scene description generation.

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/vision-ai-companion.git


## Usage
1. Navigate to the project directory:
   ```bash
   cd vision-ai-companion
## Installation and Usage
1. **Install the required dependencies**:
   ```bash
   pip install -r requirements.txt
## Run the Streamlit application:
```bash
streamlit run app.py
```

## Upload an image and choose a feature to interact with:
- **Describe Scene**
- **Extract Text**
- **Text-to-Speech**

- **Follow the on-screen instructions** for each feature.

## Credits
- Developed by: Kadir A
- GitHub: [@Kadirayyappan](https://github.com/Kadirayyappan)

