# TTS Demo (Text-to-Speech)

This repository is related to my presentation in the Spoken Language Processing class under the title **Text-to-Speech Synthesis**.

## Repository Contents:
- 📄 **Research Paper**: The paper I used as guidance for my presentation.
- 🖥️ **Presentation**: The slides I used during the class.
- 🧑‍💻 **Demo**: A demonstration showcasing two approaches to converting text into speech:

---

## 1. Local Inference using Tacotron2 and HiFiGAN

This method processes the text **locally** on your machine. It involves two steps:

- **Tacotron2**: Converts the text into a **mel-spectrogram** (a visual representation of sound frequencies).
- **HiFiGAN**: Transforms the mel-spectrogram into a **realistic speech waveform**.

🎧 The result is saved as an audio file: `generated_speech.wav`.

---

## 2. Cloud-based Inference using Amazon Polly

This method uses a **cloud service**. Text is sent to **Amazon Polly** (an AWS service), which converts it into speech.

🎤 The output is an MP3 file: `polly_speech.mp3`.

---

If you have any questions, feel free to contact me at: [y.ibork1@gmail.com](mailto:y.ibork1@gmail.com).
