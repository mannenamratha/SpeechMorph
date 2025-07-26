
# SpeechMorph

**SpeechMorph** is an automated video dubbing pipeline that:
- Extracts audio from a video.
- Transcribes speech to text using [OpenAI Whisper](https://github.com/openai/whisper).
- Translates text into the desired target language.
- Converts translated text back into speech using [gTTS](https://pypi.org/project/gTTS/).
- Synchronizes the generated audio with the original video to produce a **dubbed video**.
- Calculates performance metrics such as **TTS Duration Accuracy**.

---


## ✨ Features
- 🎥 **Video → Dubbed Video:** Fully automated multilingual dubbing.
- 🗣 **Speech-to-Text (Whisper):** Accurate transcription.
- 🌍 **Translation:** Uses `deep-translator` to support multiple languages.
- 🔊 **Text-to-Speech (TTS):** Generates natural-sounding speech.
- 📊 **Metrics:** Evaluates duration accuracy and potential transcription/translation accuracy.

---


## 📂 Project Structure
```

SpeechMorph/
│── SpeechMorph.ipynb   # Jupyter Notebook with main pipeline
│── requirements.txt    # Python dependencies
│── README.md           # Documentation

````

---

## ▶️ Usage

**Run directly in Jupyter Notebook:**
```bash
jupyter notebook SpeechMorph.ipynb
```

### Steps inside the notebook:
- Provide the path to your **input video**.  
- Enter the **target language code** (e.g., `te` for Telugu, `fr` for French, `es` for Spanish).  

### The pipeline:
- Extracts audio  
- Transcribes speech  
- Translates text  
- Synthesizes speech  
- Combines dubbed audio with the video  

**Output:** `dubbed_video.mp4`

---

## 🌐 Supported Languages

Any language supported by **Google Translator** and **gTTS**. Examples:

- `en` – English  
- `hi` – Hindi  
- `te` – Telugu  
- `fr` – French  
- `es` – Spanish  
- `de` – German  

---

## ✅ Future Enhancements

- Voice cloning for natural voice retention  
- Lip-sync accuracy improvements  
- Batch processing for multiple videos  
- Web or desktop GUI for non-technical users  
- Integration with cloud platforms for scalability  

---

## 👥 Contributors

- **M. Namratha Sai**  
- **S. Pradeep**









