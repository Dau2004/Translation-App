## Unesis Voice Translator

### Overview
The Unesis Voice Translator is an innovative application that facilitates real-time voice translation across multiple languages. Leveraging cutting-edge technologies such as AssemblyAI for speech recognition and ElevenLabs for speech synthesis, this application transcribes spoken English into text and translates it into Spanish, Kinyarwanda, and Swahili. The translated text is then converted back into speech, providing users with audio outputs in the respective languages.

### Features
- **Real-time Voice Transcription:** Transcribes spoken English into text using AssemblyAI.
- **Multi-language Translation:** Translates the transcribed text into Spanish, Kinyarwanda, and Swahili.
- **Speech Synthesis:** Converts the translated text into speech using ElevenLabs, providing audio outputs for each translated language.
- **User-friendly Interface:** A clean and intuitive interface built with Gradio allows users to easily interact with the application.

### How It Works
1. **Voice Input:** Users provide voice input through their microphone.
2. **Transcription:** The application transcribes the audio input into text using AssemblyAI.
3. **Translation:** The transcribed text is translated into Spanish, Kinyarwanda, and Swahili.
4. **Speech Synthesis:** The translated texts are converted back into speech using ElevenLabs.
5. **Output:** The application provides audio outputs and the corresponding translated text for each language.

### Getting Started
To get started with the Unesis Voice Translator, follow these steps:

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/your-repo/unesist-voice-translator.git
   cd unesis-voice-translator
   ```

2. **Install Dependencies:**
   Ensure you have Python installed. Then, install the necessary dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. **Set Up API Keys:**
   Replace the placeholders in the code with your AssemblyAI and ElevenLabs API keys:
   ```python
   aai.settings.api_key = "your_assemblyai_api_key"
   client = ElevenLabs(api_key="your_elevenlabs_api_key")
   ```

4. **Run the Application:**
   Launch the Gradio interface:
   ```bash
   python app.py
   ```

5. **Interact with the Application:**
   Open the provided local link in your browser and start using the Unesis Voice Translator.

### Usage
1. **Provide Voice Input:** Click the microphone icon to record your voice.
2. **Submit:** Click the "Submit" button to process the audio.
3. **View and Listen to Outputs:** The translated texts and corresponding audio outputs in Spanish, Kinyarwanda, and Swahili will be displayed and available for playback.

### Adding a Video Demo
To add a video demo to your README, you can follow these steps:

1. **Record the Demo:**
   Use screen recording software to capture a demonstration of the application in use.

2. **Upload the Video:**
   Upload the recorded video to a video hosting platform like YouTube.

3. **Embed the Video in README:**
   Add the following Markdown snippet to embed the video in your README file:
   ```markdown
   ## Demo

   Watch the video demonstration below to see how the Unesis Voice Translator works:

   [![Unesis Voice Translator Demo](http://img.youtube.com/vi/your_video_id/0.jpg)]([https://youtu.be/VwOvStFfGxc?si=-L_v1Nlx4YohVe_o](https://youtu.be/VwOvStFfGxc?si=kAmZ_34H0eYicoLD))
   ```



