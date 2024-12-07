# Video Content-Based Question Answering System

## Overview
This project is a pipeline for developing a solution to process videos, extract their audio, convert it to text, and train an AI model to answer user questions based on the extracted text. The model also supports browsing the internet for topic-specific information if the answer is not found in the provided content.

## Features
- **Video to Audio Conversion**: Extract audio content from video files.
- **Audio to Text Conversion**: Convert the extracted audio into text using open-source Python libraries.
- **Question-Answering Model**: Train a pre-trained language model (e.g., BERT, GPT, or T5) on the extracted text for answering user queries.
- **Web Browsing Integration**: Provide additional answers by browsing the internet, restricted to the video's specific topic.
- **Fine-Tuning Capabilities**: Train the model on topic-specific datasets (e.g., Bitcoin) for enhanced accuracy.

## Technologies Used
### Python Libraries:
- `transformers` for pre-trained language models.
- Audio processing and speech-to-text libraries (e.g., `SpeechRecognition`).
- Video processing tools (e.g., `moviepy`).

### Pre-trained Models:
- BERT, GPT, or T5 from Hugging Face's `transformers` library.

### Development Tools:
- Jupyter Notebook
- Anaconda

## Prerequisites
- Python environment setup.
- Install required dependencies:
  ```bash
  pip install transformers moviepy SpeechRecognition
  ```

## Project Workflow
### 1. Video Selection:
- Input a video file to the system.

### 2. Audio Extraction:
- Use tools like `moviepy` to extract audio from the video.

### 3. Audio-to-Text Conversion:
- Convert the extracted audio into text using open-source libraries like `SpeechRecognition`.

### 4. Model Training:
- Fine-tune a pre-trained model on the extracted text for question answering.

### 5. Question Answering:
- Input user queries.
- Provide answers from the trained model.
- If the answer is not found in the text, browse the internet for additional information.

---

