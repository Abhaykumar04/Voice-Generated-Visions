# Voice Generated Visions

**Transform your words into stunning visual art.**

## Overview
Voice Generated Visions is an innovative application that combines speech-to-text transcription with AI-driven image generation. Users can record or upload audio, have it transcribed into text using AssemblyAI, and then generate a corresponding image using Together AI. The application is built on Gradio for an interactive user interface.

![Screenshot 2024-12-31 135220](https://github.com/user-attachments/assets/2b6db776-f758-4e1d-8a84-851e61fe7614)


---

## Features
- **Audio Input:** Record your voice or upload an audio file.
- **Speech-to-Text Transcription:** Powered by AssemblyAI.
- **AI-Generated Images:** Uses Together AI to create visuals from transcribed prompts.
- **User-Friendly Interface:** Interactive and easy-to-use interface built with Gradio.

---

## Installation

### Prerequisites
- Python 3.8 or higher
- API keys for AssemblyAI and Together AI
- Required Python packages (listed in `requirements.txt`)

### Steps
1. Clone the repository:
   ```bash
   git clone <repository_url>
   cd <repository_folder>
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Configure API keys:
   - Set the `ASSEMBLYAI_API_KEY` and `TOGETHER_API_KEY` as environment variables **or**
   - Add them to an `API.yml` file in the following format:
     ```yaml
     assemblyai: YOUR_ASSEMBLYAI_API_KEY
     Together_api: YOUR_TOGETHER_API_KEY
     ```
4. Run the application:
   ```bash
   python app.py
   ```

---

## Usage
1. Open the application in your browser (Gradio will provide a local URL).
2. Record or upload audio:
   - Use the microphone icon to record your voice.
   - Or upload an audio file from your device.
3. Generate Vision:
   - Click **Generate Vision** to process your audio.
   - The transcribed text will appear, followed by a generated image.
4. View results:
   - Review the transcription.
   - Download or share the generated image.

---

## File Structure
```
.
├── app.py               # Main application file
├── requirements.txt     # Python dependencies
├── API.yml              # Configuration file for API keys (optional)
├── README.md            # Project documentation
```

---

## API Integration
- **AssemblyAI:**
  - Handles audio transcription.
  - [AssemblyAI Documentation](https://www.assemblyai.com/docs/)
- **Together AI:**
  - Generates images based on text prompts.
  - [Together AI Documentation](https://www.together.xyz/)

---

## Technologies Used
- **Gradio:** For building the user interface.
- **AssemblyAI:** For speech-to-text processing.
- **Together AI:** For generating visuals.
- **Python Libraries:**
  - `gradio`
  - `assemblyai`
  - `together`
  - `PIL`
  - `PyYAML`

---

## Contributing
Contributions are welcome! Please follow these steps:
1. Fork the repository.
2. Create a new branch (`feature-branch`):
   ```bash
   git checkout -b feature-branch
   ```
3. Commit your changes:
   ```bash
   git commit -m "Description of changes"
   ```
4. Push to the branch:
   ```bash
   git push origin feature-branch
   ```
5. Open a Pull Request.

---

## License
This project is licensed under the MIT License. See the `LICENSE` file for details.

---

## Acknowledgements
- [Gradio](https://gradio.app/)
- [AssemblyAI](https://www.assemblyai.com/)
- [Together AI](https://www.together.xyz/)

