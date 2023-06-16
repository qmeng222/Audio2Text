# Audio2Text

## About the project:

- Description: Convert audio files into accurate and reliable text transcriptions using Whisper AI.
- Tech stack:
  - Programming language: Python
  - Computing platform: Jupyter Notebook
  - Speech recognition model: whisper-1
  - Version control: Git, GitHub
- Overview:

## Setup:

1. Create & activate the virtual environment (and all subsequent steps will be performed within the virtual environment):
   ```
   python -m venv .venv
   source .venv/bin/activate
   ```
2. Upgrade the pip package manager to the latest version within the current Python environment: `python -m pip install --upgrade pip`
3. Install Jupyter, and configure a kernel specifically for the virtual environment.
   - Install Jupyter in the virtual environment (so that I can use Jupyter notebooks within the virtual environment): `pip install jupyter`
   - Install ipykernel within the virtual environment (to create and manage kernels for Jupyter notebooks): `pip install ipykernel`
   - Create and install a kernel specifically for the virtual environment: `python -m ipykernel install --user --name=myenv`
4. Install libraries/packages:
   - install OpenAI: `pip install openai`
   - Install the python-dotenv package: `pip install python_dotenv`
   - Install the PortAudio library to provide audio input and output capabilities: `brew install portaudio`
   - Install the PyAudio library to access and manipulate audio streams: `pip install pyaudio`
5. Generate a snapshot of the installed packages and their versions to the requirements.txt file (or overwrite the txt file): `pip freeze > requirements.txt`, so others can install all the packages and their respective versions specified in the requirements.txt file with `pip install -r requirements.txt`

## Resources:

1. [OpenAI API reference](https://platform.openai.com/docs/api-reference)
2. [How to turn audio into text](https://platform.openai.com/docs/api-reference/audio)
3. [How to translates audio into English](https://platform.openai.com/docs/api-reference/audio/create)
4. [About the Whisper model](https://platform.openai.com/docs/models/whisper)
5. [The open source version of Whisper](https://github.com/openai/whisper)
