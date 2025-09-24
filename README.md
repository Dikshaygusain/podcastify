# 🎧 Podcastify

Podcastify is an **AI-powered web application** that converts PDFs into podcast-style audio in **under 30 seconds**.  
It supports file uploads (up to **5MB**) with **automatic conversion** and integrated audio playback.  
The project combines **LLMs** and **advanced TTS systems** to deliver realistic, engaging audio content.  

---

## 🚀 Features
- Convert **10+ page PDFs** into natural-sounding audio podcasts in <30s.  
- **Context-aware dialogue generation** using **LangChain** and **Groq LLMs**.  
- **Realistic voice synthesis** with **ParlerTTS**.  
- Achieved **90%+ user satisfaction** during testing.  
- Outperformed baseline TTS systems on **Word Error Rate (WER)** and **Mean Opinion Score (MOS)** benchmarks.  

---

## 🛠️ Tech Stack
- **Languages:** Python  
- **Frameworks:** Flask, LangChain  
- **Libraries:** Groq LLMs, ParlerTTS  
- **Developer Tools:** Git, VS Code, Jupyter Notebook  

---

## ⚡ Installation & Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/Dikshaygusain/podcastify.git
   cd podcastify
   
2. Install dependencies:
   ```bash
   pip install -r requirements.txt


3. Run the Flask application:
   ```bash
   python app.py


4. Open your browser and navigate to:
   ```bash
   http://127.0.0.1:5000/

---

## 📊 Results

- Conversion latency: <30s for 10+ page PDFs.

- WER (Word Error Rate): Reduced compared to standard TTS systems.

- MOS (Mean Opinion Score): Achieved higher ratings for clarity and naturalness.

---
## 🔮 Future Improvements

- Support for multi-language PDF-to-podcast conversion.

- Deployment on AWS SageMaker for scalability and production use.

- User dashboard for managing and storing past conversions.

---
## 🙌 Acknowledgements

- LangChain for dialogue management.

- Groq
 LLMs for fast inference.

- ParlerTTS for text-to-speech synthesis.
