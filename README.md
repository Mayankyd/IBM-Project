# 🌟 AI Poetry Generator

## 📖 Project Overview

**AI Poetry Generator** is a creative and interactive application that generates expressive, structured, and thematically rich poetry based on user-defined inputs such as **themes**, **emotions**, **styles**, and **poetic forms**. Leveraging powerful generative AI models, this project blends artificial intelligence with human creativity—pushing the boundaries of NLP to produce emotionally resonant and aesthetically compelling poems.

---

## 🎯 Features

- **🎨 Customizable Themes:** Choose from themes like love, nature, adventure, and more.
- **💫 Emotional Depth:** Generate poems with tones of joy, nostalgia, melancholy, excitement, etc.
- **✍️ Poetic Form Support:** Includes Sonnets, Haikus, Odes, and Free Verse.
- **🖥️ Interactive UI:** Built with Streamlit for seamless real-time interaction.
- **💾 Save & Share:** Download your generated poems for future reading or sharing.
- **🧠 Prompt Experimentation:** Modify prompts to explore the AI’s stylistic flexibility.

---

## 🛠️ Technologies Used

- **Python** – Core backend logic.
- **HuggingFace Transformers** – Utilizes GPT-2, GPT-3, or Mistral for text generation.
- **Streamlit** – For building the front-end interface.
- **Jupyter Notebook / Google Colab** – Used for model experimentation and testing.

---

## 🧱 Project Architecture

```plaintext
┌──────────────────────┐
│     Streamlit UI     │ ◄─── User Inputs (Theme, Emotion, Style, Form)
└────────┬─────────────┘
         │
         ▼
┌────────────────────────────┐
│ Structured Prompt Creation │
└────────┬───────────────────┘
         │
         ▼
┌───────────────────────────┐
│ HuggingFace Transformer   │ ◄── Pre-trained LLM (e.g., GPT-2/GPT-3)
└────────┬──────────────────┘
         │
         ▼
┌───────────────────────────┐
│  Real-time Poetry Output  │
└───────────────────────────┘
