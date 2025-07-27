# Medical-Report-Summarization
This project uses a pre-trained large language model (LLM) to automatically summarize lengthy medical reports like diagnostics, lab results, and clinical documents into short, human-readable insights for doctors and patients.

---

Features

- Extracts text from PDF or text-based medical files
- Summarizes using Flan-T5 (instruction-tuned LLM)
- Helps in quick diagnosis, triage, and EMR (Electronic Medical Record) systems
- Runs on Google Colab with minimal setup

Tech Stack

- Python 
- [Transformers by Hugging Face](https://huggingface.co/docs/transformers/index)
- Flan-T5 (google/flan-t5-large)
- Google Colab (for easy GPU access)
- PDF processing with pypdf
