# Granite 4.1 3B Oracle Text-to-SQL

A fine-tuned IBM Granite 4.1 3B model for generating Oracle SQL from natural-language questions.

## Downloads

- [Hugging Face GGUF — LM Studio / llama.cpp](https://huggingface.co/Vakamalla-Anitha/granite-4.1-3b-oracle-nl2sql-gguf)
- [Kaggle model and usage notebook](https://www.kaggle.com/models/anithavakamalla/oracle19c-nl2sql-granite-4-1-3b-gguf)

## Model Format

The public GGUF release uses Q4_K_M 4-bit quantization for efficient local inference.

## Usage

Load the GGUF file in LM Studio or run it with llama.cpp-compatible tools.

Always validate generated SQL against your database schema, permissions, and business rules before use.
