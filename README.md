# Lightweight Fine-Tuning of GPT-2 with LoRA

*This project implements PEFT (Parameter-Efficient Fine-Tuning) of the GPT-2 language model for sentiment classification on the IMDb dataset using the LoRA (Low-Rank Adaption) technique supported by Hugging Face's `peft` framework.*

---

## Workflow overview


- Loading and evaluating a pre-trained GPT-2 model.
- Performing LoRA-based fine-tuning using PEFT.
- Running inference with the fine-tuned model.
- Comparing performance between the original and fine-tuned models.

---

## Libraries

- [PyTorch](https://docs.pytorch.org/docs/2.13/index.html#)
- [Hugging Face Transformers](https://huggingface.co/docs/transformers/en/index)
- [Hugging Face PEFT](https://huggingface.co/docs/peft/en/index)

---

## Dataset

- IMDb (via [Hugging Face Datasets library](https://huggingface.co/datasets/stanfordnlp/imdb))

---
