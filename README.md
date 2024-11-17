# VaaniVriksha
# Kannada Speech-Based Question Answering System

This project focuses on building a pipeline to process audio data related to sandalwood cultivation in Kannada. It leverages Automatic Speech Recognition (ASR) to transcribe audio files and facilitates question-answering through natural language processing techniques.  

---

## Features
- **Audio Transcription:** Converts Kannada audio into text (transcriptions).
- **Multilingual Support:** Includes translations of transcriptions into English.
- **Custom Tokenizer:** Developed a tokenizer for efficient text processing.
- **Question Answering:** Enables users to input questions in Kannada as speech and retrieves relevant answers from the transcribed dataset.

---

## Dataset
The dataset consists of audio recordings in Kannada, primarily discussing sandalwood cultivation. The recordings are colloquial and may contain background noise, adding complexity to transcription and processing.

### Dataset Details:
- **Source:** Scraped from YouTube.
- **Format:** CSV file with the following columns:
  - Audio Path
  - Kannada Transcription
  - English Translation

---

## Current Progress
1. **Dataset Creation:** 
   - Transcriptions of audio files in Kannada.
   - English translations of the transcriptions for broader utility.
2. **Tokenizer Development:**
   - Built a custom tokenizer for efficient text tokenization.
3. **Audio Input Pipeline:** 
   - Designed an input pipeline to capture user questions in Kannada as audio.

---

## Challenges
- **Training the ASR Model:**
  - The session crashed multiple times during the training phase, leading to a lack of progress in fine-tuning the model.
- **Technical Issues:**
  - Failed installation of essential dependencies like `pyaudio` caused delays.
- **Hardware Limitations:**
  - Limited computational resources hindered training and processing.

---


## Setup Instructions
1. **Clone the Repository:**
   ```bash
   git clone <https://github.com/madhumeeta27/VaaniVriksha.git>
   cd <VaaniVriksha>
