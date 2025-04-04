# Viongozi: An AI Language Buddy for Underrepresented Dialects

**Viongozi** (Swahili for "Leaders") is a student-led AI capstone project built during the Kenya IOAI 2025 mentorship program. 
It aims to empower local communities by providing tools for language identification and translation across underrepresented African dialects.

## Project Overview

Viongozi is a lightweight AI assistant that:
- Identifies dialects in short text snippets (e.g., Kikuyu, Dholuo, Sheng)
- Translates or explains these into English
- Optionally supports speech via TTS/STT

The goal is to highlight the importance of inclusive NLP, especially for low-resource language contexts.

## Objectives

- Develop an AI pipeline for dialect classification using machine learning
- Explore LLM-based translation or rule-based language explanation
- Build a user-facing CLI or web prototype
- Raise awareness of the underrepresentation of African languages in NLP

## Tech Stack

- Python (3.9+)
- Scikit-learn
- Pandas, NumPy
- HuggingFace Transformers
- fastText (baseline)
- Streamlit (for UI prototype)
- Google Colab

## Folder Structure

```
viongozi-ai-language-buddy/
├── data/               # Raw and processed language samples
├── notebooks/          # Colab notebooks for experimentation
├── models/             # Saved model files
├── src/                # Core Python scripts
├── proposal/           # Project proposal and documentation
├── requirements.txt    # Dependencies
└── README.md           # This file
```

## Getting Started

Clone this repo:
```bash
git clone https://github.com/your-username/viongozi-ai-language-buddy.git
cd viongozi-ai-language-buddy
```

Install dependencies:
```bash
pip install -r requirements.txt
```

Run the CLI (once ready):
```bash
python src/app.py
```

Or launch the Streamlit app:
```bash
streamlit run src/app.py
```

## Acknowledgments

- [Masakhane](https://www.masakhane.io/) — for championing open NLP research in African languages
- Microsoft Research Africa — for leadership in inclusive AI
- IOAI — for inspiring the next generation of AI leaders

---

> Developed by students in Kenya under the mentorship of Millicent — NLP researcher, WiDS Ambassador, and advocate for multilingual inclusivity in AI.
