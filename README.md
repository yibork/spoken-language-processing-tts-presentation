# TTS Demo (Text-to-Speech)

This repository is related to my presentation in the Spoken Language Processing class under the title **Text-to-Speech Synthesis**. 
The repository contains:
The repository contains:
- The paper which I used as guidance for my presentation.
- The presentation used during the class.
- A demo showcasing two approaches to converting text into speech:
## Local Inference using Tacotron2 and HiFiGAN:
A model that processes the text on your machine. It converts the text into speech using two models:

- **Tacotron2**: Converts the text into a mel-spectrogram.
- **HiFiGAN**: Converts the mel-spectrogram into audio (a realistic speech waveform).

The result is saved as an audio file (`generated_speech.wav`) on your machine.

## Cloud-based Inference using Amazon Polly:
A cloud service that takes text, sends it to Amazon Polly (an AWS service), and gets back the speech audio in MP3 format. The audio file is saved as `polly_speech.mp3`.
