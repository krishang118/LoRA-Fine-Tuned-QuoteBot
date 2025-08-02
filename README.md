# GPT-2 QuoteBot Fine-Tuning with LoRA (PEFT)
 
This project fine-tunes the GPT-2 model for generating quotes, using the [Abirate/english_quotes](https://huggingface.co/datasets/Abirate/english_quotes) dataset. It leverages Parameter-Efficient Fine-Tuning (PEFT) with LoRA adapters for efficient training and inference.

## Features

- Fine-tunes GPT-2 to generate quote-style outputs
- Uses LoRA (Low-Rank Adaptation) for robust parameter-efficient training
- Evaluates model performance using perplexity
- Saves and loads trained fine-tuned models and configuration for easy reuse

## How to Run

1. Make sure that Python 3.8+ is installed.
2. Clone this repository on your local machine.
3. Open and run the first cell of the `Finetune.ipynb` Jupyter Notebook file to install the required dependencies.
4. Now, run the second cell, which is basically the LoRA fine-tuning script. To avoid retraining from scratch, you can directly download and extract the folder containing the fine-tuned model files from this [Google Drive Link](https://drive.google.com/file/d/1pq9fib-2soldz8OO7rb_0_JBwKdS3L3n/view?usp=sharing). Place the extracted folder in the root project directory, and the already trained fine-tuned model will be loaded in automatically.
5. After the QuoteBot is set up, quote topics can be entered as prompts to generate the required quotes.

## Contributing

Contributions are welcome!

## License

Distributed under the MIT License. 
