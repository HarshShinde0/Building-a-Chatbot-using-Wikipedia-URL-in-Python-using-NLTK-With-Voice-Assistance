# Building a Chatbot using Wikipedia URL in Python (with NLTK & Voice Assistance)

This project demonstrates how to build a **simple chatbot** that leverages the content of any Wikipedia page as its knowledge base. It is built in Python using **NLTK** for Natural Language Processing, and includes **voice assistance** for both input and output, making the interaction more natural and engaging.

---

## 🧠 Project Overview

- **Input a Wikipedia URL:** The chatbot scrapes and processes text from the specified Wikipedia page.
- **NLP with NLTK:** The text is cleaned, tokenized, and lemmatized to prepare it for chat interactions.
- **Conversational Interface:** Users can ask questions about the Wikipedia page content.
- **Voice Assistance:** The chatbot can accept voice input and provide spoken responses, in addition to text.

---

## 🚀 Features

- Web scraping from any Wikipedia URL
- Text preprocessing and TF-IDF based matching using NLTK
- Interactive Q&A chatbot
- Voice input (speech recognition)
- Voice output (text-to-speech)

---

## 🛠️ Installation & Setup

1. **Clone the Repository**
    ```bash
    git clone https://github.com/HarshShinde0/Building-a-Chatbot-using-Wikipedia-URL-in-Python-using-NLTK-With-Voice-Assistance.git
    cd Building-a-Chatbot-using-Wikipedia-URL-in-Python-using-NLTK-With-Voice-Assistance
    ```

2. **Install Required Packages**
    ```bash
    pip install nltk requests beautifulsoup4 scikit-learn SpeechRecognition pyttsx3 pyaudio
    ```

    > **Note:**  
    > - `pyaudio` may require additional system dependencies.  
    > - For Jupyter Notebook, use `!pip install ...` inside a cell.

3. **Download NLTK Data (First Run Only)**
    ```python
    import nltk
    nltk.download('punkt')
    nltk.download('wordnet')
    ```

4. **Run the Notebook**
    - Open the notebook:
      ```
      jupyter notebook "Building a Simple Chatbot using Wikipedia URL in Python (using NLTK) With Voice Assistance.ipynb"
      ```
    - Follow the instructions in the notebook cells.

---

## 💡 How It Works

1. **Provide a Wikipedia URL:**  
   The notebook fetches and processes the text content from the given Wikipedia link.

2. **Ask Questions (by Text or Voice):**  
   Users can ask questions in the notebook interface or by speaking.

3. **Get Answers (by Text and Voice):**  
   The chatbot returns the most relevant sentence(s) using TF-IDF similarity, and reads out the answer using text-to-speech.

---

## 📄 Example Usage

- Enter a Wikipedia URL (e.g., [https://en.wikipedia.org/wiki/Artificial_intelligence](https://en.wikipedia.org/wiki/Artificial_intelligence))
- Interact with the chatbot using text or voice queries about that topic
- Receive accurate, context-aware answers spoken aloud

---

## 🤝 Contributing

Pull requests, issues, and suggestions are welcome!  
Feel free to fork the repo and contribute.

---

## 📄 License

This project is open-source and available under the MIT License.

---

## 🙋‍♂️ Author

- **Harsh Shinde**  
  [GitHub Profile](https://github.com/HarshShinde0)

---

*If you found this project helpful, please ⭐ star the repository!*
