
# Text-to-Speech Synthesis Using Transformers

This repository demonstrates how to use a pre-trained text-to-speech (TTS) model from the Hugging Face Transformers library to convert text into spoken audio. The project uses the `microsoft/speecht5_tts` model to generate speech and allows customization of the speaker's voice by utilizing speaker embeddings from the `cmu-arctic-xvectors` dataset.

## Features
- **Text-to-Speech Conversion**: Easily convert text into speech using a state-of-the-art TTS model.
- **Speaker Embeddings**: Personalize the generated voice by selecting from a set of predefined speaker embeddings.
- **Audio Output**: Save the generated speech as a high-quality WAV file.

## Getting Started

### Prerequisites
Ensure you have Python 3.x installed on your machine. You'll also need to install the required Python packages.

### Installation

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/utkarshkr13/text-to-speech-synthesis.git
   cd text-to-speech-synthesis
   ```

2. **Install Dependencies**:
   Install the required Python libraries using `pip`:
   ```bash
   pip install -r requirements.txt
   ```

### Usage

To generate speech from text, run the `texttospeech.py` script:

```bash
python texttospeech.py
```

The script will:
1. Load the text-to-speech model.
2. Retrieve speaker embeddings from the dataset.
3. Convert the provided text into speech using the selected speaker's voice.
4. Save the generated audio as `speech.wav`.


### Example

In the current script, the text `"Major League Hacking Hackathons are so cool"` is converted into speech using the voice of a specific speaker from the `cmu-arctic-xvectors` dataset. The output is saved as `speech.wav` in the current directory.

### File Structure

- `text_to_speech.py`: Main script for running the text-to-speech synthesis.
- `requirements.txt`: List of dependencies required to run the project.
- `README.md`: Documentation for the project.

### License

This project is licensed under the MIT License - see the `LICENSE` file for details.

### Acknowledgments

- [Hugging Face](https://huggingface.co/) for providing the Transformers library and pre-trained models.
- [CMU Arctic](http://festvox.org/cmu_arctic/) for the speaker embeddings dataset.

---
