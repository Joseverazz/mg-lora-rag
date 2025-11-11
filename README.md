# mg-lora-rag

Notebook-first experiments for LoRA fine-tuning and comparison of two models (Gemma 3 4B and Llama 3.2 3B Instruct).

This repository contains the primary experiment notebook and a small scaffolding to make parts of the workflow reproducible from scripts.

Try the lightweight dataset loader (will download a small sample via Hugging Face datasets):

PowerShell example:

```powershell
python -m pip install -r requirements.txt
python .\scripts\train.py --max-samples 5
```
