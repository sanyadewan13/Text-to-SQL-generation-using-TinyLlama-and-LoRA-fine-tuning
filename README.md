# Text-to-SQL Generation using LoRA Fine-Tuning

This project demonstrates parameter-efficient fine-tuning of TinyLlama using LoRA (Low-Rank Adaptation) to convert natural language queries into SQL statements. The model is trained on a Text-to-SQL dataset and learns to generate structured SQL queries from user questions and database schemas.

## Key Features

* Fine-tuned TinyLlama using LoRA and PEFT
* Natural Language to SQL conversion
* Hugging Face Transformers and TRL integration
* Google Colab training workflow
* Memory-efficient fine-tuning on T4 GPU
* End-to-end inference pipeline for SQL generation

## Technologies Used

* Python
* Hugging Face Transformers
* PEFT (LoRA)
* TRL (SFTTrainer)
* PyTorch
* Google Colab

## Project Outcome

The fine-tuned model generates more structured and concise SQL queries compared to the base model, demonstrating the effectiveness of LoRA for task-specific adaptation with limited computational resources.

## Future Improvements

* Train on larger Text-to-SQL datasets
* Evaluate SQL execution accuracy
* Experiment with larger LLMs such as Qwen and Llama models
* Add a web interface for real-time query generation
