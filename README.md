# Megat-tokenizer v0.1

![MEGAT Logo](MEGATLogo.png)

Welcome to Megat-tokenizer v0.1! This tokenizer is specifically designed for tokenizing literature works written by Megat. The goal is to build a custom Language Model (LLM) that can generate new works based on Megat's own dataset. This tokenizer serves as the first step towards achieving that goal.

## Features

1. **Custom Tokenization:** Tokenizer tailored to my literature works.
2. **Fast Training:** Able to train the tokenization model on my works in around 3-4 minutes on a MacBook M1
3. **Easy Testing:** Users can test the code using pytest. Simply ensure they have pytest installed (`pip install pytest`) and run the following command:
   ```sh
   $ pytest -v .

## Usage

To use this repository you may,
1. Clone the repository via CLI command below:
   ```sh
   $ git clone https://github.com/your-username/Megat-tokenizer.git

2. Install dependencies
   ```sh
   $ pip install regex tiktoken
3. Train the tokenizer
   ```sh
   from maercbpe import RegexTokenizer

   tokenizer = RegexTokenizer()
   tokenizer.train(very_long_training_string, vocab_size=32768)


