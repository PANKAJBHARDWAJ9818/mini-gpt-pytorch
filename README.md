# Mini GPT (PyTorch)

A custom decoder-only Transformer language model built from scratch in PyTorch, inspired by nanoGPT. Trained locally and on Google Colab using the Tiny Shakespeare dataset.

# Architecture Highlights
* **Decoder-Only Transformer:** Implements multi-head self-attention, masked attention heads, and positional embeddings.
* **Data Pipeline:** Uses `tiktoken` for subword tokenization and `numpy.memmap` for efficient memory-mapped dataset handling.
* **Model Scale:** ~13.72M parameter base configuration designed for local experimentation.

# Project Structure
* `mini_gpt.ipynb` - The full pipeline notebook covering data tokenization, model definition, training loop, and text generation.
* `mini_gpt_model.pt` - Pre-trained model weights.

# How to Run
1. Clone the repository:
   ```bash
   git clone [https://github.com/PANKAJBHARDWAJ9818/mini-gpt-pytorch.git](https://github.com/PANKAJBHARDWAJ9818/mini-gpt-pytorch.git)
