
## Text-to-Speech Synthesis Using Transformers

This repository contains a Python script that demonstrates how to use a pre-trained text-to-speech model from the Hugging Face Transformers library to convert text into spoken audio. The project leverages the `microsoft/speecht5_tts` model to synthesize speech in the style of a specific speaker, using speaker embeddings from the `cmu-arctic-xvectors` dataset.

### Features:
- **Text-to-Speech Conversion**: Convert any given text into speech using a state-of-the-art TTS model.
- **Speaker Embeddings**: Customize the synthesized voice by selecting different speaker embeddings.
- **Audio Output**: Save the generated speech as a WAV file.

### How to Use:
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-username/text-to-speech-synthesis.git
   ```
2. **Install Dependencies**:
   ```bash
   pip install -r requirements.txt
   ```
3. **Run the Script**:
   ```bash
   python text_to_speech.py
   ```

### Requirements:
- Python 3.x
- Transformers library
- Datasets library
- Soundfile
- PyTorch

### Getting Started:
Follow the instructions in the `README.md` file to set up and run the project. You can modify the text input or experiment with different speaker embeddings to customize the output.

### License:
This project is licensed under the MIT License. See the `LICENSE` file for details.
