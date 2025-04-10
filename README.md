# Fine-Tuning Transformer Models on SQuAD & LaTeX Dataset

This project demonstrates fine-tuning a FLAN-T5 model on a custom LaTeX-based QA dataset and SQuAD using the Unsloth framework with QLoRA.

## 🚀 Features
- LaTeX-to-Natural Language mapping for math Q&A.
- Utilizes Unsloth + QLoRA for efficient fine-tuning.
- Supports symbolic math tasks and accessibility use cases.

## 📁 Files
- `Finetune_LaTeX_SQuAD.ipynb`: Full Colab training notebook.
- `data/sample_dataset.json`: Example of custom LaTeX QA data.

## 📦 Requirements
```bash
pip install unsloth transformers datasets accelerate
```

## 🔧 Model & Training
- Model: `FLAN-T5-Small`
- Data: SQuAD + LaTeX-based QA pairs
- LoRA: QLoRA adapter training
- Framework: [Unsloth](https://github.com/unslothai/unsloth)

## 📄 License
MIT License
