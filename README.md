# Megat-tokenizer v0.1

Welcome to Megat-tokenizer v0.1! This tokenizer is specifically designed for tokenizing literature works written by Megat. The goal is to build a custom Language Model (LLM) that can generate new works based on Megat's own dataset. This tokenizer serves as the first step towards achieving that goal.

## Features

1. **Custom Tokenization:** Tokenizer tailored to Megat's literature works.
2. **Fast Training:** Able to train the tokenization model on Megat's works in around 3-4 minutes on a MacBook.
3. **Easy Testing:** Users can test the code using pytest. Simply ensure they have pytest installed (`pip install pytest`) and run the following command:
   ```sh
   $ pytest -v .
