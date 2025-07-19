# 🎙️ Record and Transcribe Audio Using Ctranslate2!\
<img width="925" height="387" alt="image" src="https://github.com/user-attachments/assets/33e30816-7ee8-4450-9adb-153c06457a4a" />


An efficient and user-friendly desktop application for converting speech to text, optimized for CPU performance.

## ✨ Key Features
- 🎤 Record and transcribe audio in real-time
- 📝 Automatic transcription to clipboard
- 🔍 Multiple Whisper model options
- ⚡ Optimized for speed using CTranslate2
- 💻 CPU-optimized performance
- 🎵 Support for various audio formats


## 💻 System Requirements

### Essential Requirements
1. [Python 3.11](https://www.python.org/downloads/release/python-3119/) or [Python 3.12](https://www.python.org/downloads/release/python-31210/)
2. [Git](https://git-scm.com/downloads)
3. [git-lfs](https://git-lfs.com/)
4. Windows OS
   > Linux and MacOS support planned for future releases

### Recommended Specifications
- 8GB RAM (4GB minimum)
- Modern multi-core CPU
- Microphone for recording

## 🚀 Installation

### Step 1: Setup
1. Download the latest release (ZIP file)
2. Extract the contents to your preferred location
3. Navigate to the folder containing `main.py`
4. Create a virtual environment:
   ```bash
   python -m venv .
   ```

### Step 2: Activation
Activate the virtual environment:
```bash
.\Scripts\activate
```

### Step 3: Installation
Run the installation script:
```bash
python install.py
```

The installer will automatically:
- Verify Python version
- Set up the optimized environment
- Install required packages
- Configure optimal settings for your system

## 🎯 Usage Guide

### Step 1: Launch
1. Activate the virtual environment and start the program:
   ```bash
   python main.py
   ```

### Step 2: Configure
1. Choose your preferred Whisper model
2. Click "Update Settings"
   > First-time use will automatically download the selected model

### Step 3: Transcribe
1. Click "Start Recording"
2. Speak clearly into your microphone
3. Click "Stop Recording"
4. The transcription is automatically copied to clipboard
5. Paste (`Ctrl+V`) into any application

### Additional Features
- 📝 Edit transcriptions before copying
- 🔄 Switch between different Whisper models
- 💾 Save transcriptions to file
- ⏱️ View word timestamps

### Tips for Best Results
1. Use a good quality microphone
2. Speak clearly and at a moderate pace
3. Minimize background noise
4. Keep optimal distance from microphone

![Application Interface](https://github.com/user-attachments/assets/04d5f36c-11af-4247-8347-b51c17119aff)

> Note: The transcription is automatically copied to clipboard. Use the "Copy to Clipboard" button to copy edited versions.
