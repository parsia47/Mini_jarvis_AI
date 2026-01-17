# Mini JARVIS AI Assistant

A voice-enabled conversational AI assistant built with Python and Hugging Face Transformers.  
Supports multi-turn dialogue, contextual memory, and real-time voice responses via gTTS.

---

## Features
- Conversational AI powered by a transformer-based language model (FLAN-T5)
- Multi-turn chat with contextual memory and prompt engineering
- Text-to-speech voice responses (gTTS)
- Browser-based interface using Gradio
- Quick example prompts built in for easy demo:
  - “Introduce yourself”
  - “Tell me a joke”
  - “Explain AI simply”
  - “Give me a fun fact”

---

## Tech Stack
- Python
- Hugging Face Transformers
- PyTorch
- Gradio
- gTTS (Google Text-to-Speech)

---

## How to Run

You can run Mini JARVIS directly in **Google Colab**:

1. Open `Mini-Jarvis.py` in Colab.  
2. Uncomment the first line if needed:

```python
# !pip install transformers gradio torch accelerate gTTS -q
