# pyannote-diarization
# Speaker Diarization with PyAnnote

This repository contains a Python implementation for speaker diarization using the `pyannote.audio` library. It splits long audio files into smaller chunks and processes them to identify different speakers.

## Usage

1. **Prepare your audio file**: Ensure your audio file is in WAV format. Place it in the specified directory (e.g., `/kaggle/input/wav/`).

2. **Run the script**: The script reads the audio file, splits it into chunks, and performs speaker diarization. You can modify the chunk duration in seconds as needed.

3. **Check the output**: The results will be printed to the console, showing the start and end times for each detected speaker segment.

- **Audio Splitting**: The code includes a function to split audio files into smaller chunks for processing.
- **Speaker Diarization**: The `pyannote.audio` library is used to identify and label different speakers in the audio.
- **GPU Support**: If a compatible GPU is available, the pipeline is moved to GPU for faster processing.
