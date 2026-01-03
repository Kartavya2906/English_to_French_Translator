# English to French Translator 🇬🇧➡️🇫🇷

This project is a simple **English to French Language Translator** built using **Hugging Face Transformers** and **Google Text-to-Speech (gTTS)**.  
It translates English text into French and can also **play audio** for both the English input and the French output.

---

## 📌 Features

- 🔤 Translate English text to French
- 🤖 Uses a **pretrained MarianMT model** from Helsinki-NLP
- 🔊 Text-to-Speech support for:
  - English input
  - French translated output
- 🚀 Easy to run on **Google Colab**

---

## 🧠 Model Used

- **Model:** `Helsinki-NLP/opus-mt-en-fr`
- **Framework:** Hugging Face `transformers`
- **Type:** Sequence-to-sequence Neural Machine Translation (NMT)

---

## 🛠️ Technologies & Libraries

- `transformers` – for loading and running the translation model  
- `sentencepiece` – tokenizer backend  
- `gTTS` – Google Text-to-Speech  
- `IPython.display.Audio` – to play generated audio  
- `Python`

---

## 📂 Project Structure

English_to_French_Translator.ipynb
README.md


---

## ▶️ How to Run (Google Colab Recommended)

1. Open the notebook in **Google Colab**
2. Run the installation cells:
   ```python
   !pip install transformers sentencepiece
   !pip install gTTS
3.Execute all cells in order
4.Call the translation function:
translate_to_french("I love artificial intelligence")
5. Use text-to-speech:
recite_en("Hello, how are you?")
recite_fr("Bonjour, comment ça va ?")

🧪 Example

Input (English):

I am learning machine learning


Output (French):

J'apprends l'apprentissage automatique


🔊 Audio playback is generated automatically.

⚠️ Notes

Internet connection is required (model download + gTTS)

Audio file (audio.mp3) gets overwritten on each run

Best suited for short to medium-length sentences

🎯 Learning Outcomes

Understand how pretrained NLP models work

Learn sequence-to-sequence translation

Integrate NLP with Text-to-Speech

Gain hands-on experience with Hugging Face APIs

📌 Future Improvements

Support for multiple languages

Web UI using Streamlit / Flask

Speech-to-text input

Save translation history

👤 Author

Kartavya Gupta
