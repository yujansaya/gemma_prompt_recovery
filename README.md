# Prompt Recovery with Gemma
The project aims to generate prompts for essay rewriting by fine-tuning a pre-trained language model on a dataset of original and rewritten texts. It involves loading the model, preparing the data, training the model, and then utilizing the trained model to generate prompts based on provided texts, ultimately producing a CSV file containing the generated prompts for further analysis or evaluation.

## Tools and Dependencies:
- Python programming language
- Accelerate library for efficient distributed training
- Transformers library for natural language processing tasks
- PyTorch library for tensor computations
- Pandas library for data manipulation
- tqdm library for progress bars
- 
## Techniques:
- Language model fine-tuning: The script fine-tunes a pre-trained language model on a dataset of original and rewritten texts to adapt it for prompt generation.
- Tokenization: The text data is tokenized using the AutoTokenizer from the Transformers library.
- Prompt generation: Prompts are generated based on the original and rewritten texts using the fine-tuned language model.
- Data preprocessing: The training data is preprocessed, including tokenization and formatting, to prepare it for model training.
- Model training: The fine-tuned language model is trained using a specified configuration, including hyperparameters and optimization settings.
- Result storage: The generated prompts are stored in a DataFrame and saved to a CSV file for further analysis or evaluation.
