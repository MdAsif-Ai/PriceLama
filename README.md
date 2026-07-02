# PriceLlama

**PriceLlama** is a fine-tuned **Llama 3.2 3B** model specialized in estimating product prices from natural language descriptions. The model has been instruction-tuned to better understand product attributes, specifications, and contextual information in order to generate accurate price estimates.

The model was trained using modern parameter-efficient fine-tuning techniques, including **QLoRA**, **4-bit NF4 quantization**, **LoRA adapters**, and the Hugging Face **Transformers**, **PEFT**, and **TRL** libraries. This approach enables efficient training while preserving the strong reasoning capabilities of the underlying foundation model.

## Features

* Predicts prices directly from product descriptions
* Fine-tuned from Llama 3.2 3B
* Parameter-efficient training using QLoRA
* Optimized for inference with low memory requirements
* Compatible with the Hugging Face Transformers ecosystem

## Repository

The model is available on Hugging Face:

**🤗 Hugging Face:**
https://huggingface.co/Md-Asif/PriceLlama

## Notes

PriceLlama is intended for research, experimentation, and educational purposes. Prediction quality depends on the product category, the completeness of the description, and the distribution of the training data. The generated prices should be considered estimates rather than authoritative market values.
