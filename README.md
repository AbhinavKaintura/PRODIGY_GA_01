# PRODIGY_GA_01
## Aim:
The goal of this project was to fine-tune a pre-trained GPT-2 model (specifically GPT-2 Medium) using PyTorch to generate coherent and contextually relevant text based on a custom dataset.

## How I Achieved the Goal:
To achieve this, I used the Hugging Face transformers library and loaded the GPT-2 Medium model. I prepared a custom text dataset, tokenized it, and then fine-tuned the model using training arguments tailored to the task. After training, I enhanced text quality by adjusting parameters like temperature, top-k sampling, top-p sampling, and repetition penalty to improve coherence and creativity during text generation.

## Challenges and How I Addressed Them:
#### Quality of Generated Text: Initially, the generated text lacked coherence. To fix this, I tuned hyperparameters such as temperature and applied sampling strategies (top-k, top-p) to balance randomness and creativity.
#### Model Convergence: Training with limited data led to convergence issues. I addressed this by increasing the number of training epochs and ensuring the dataset was cleaned and diverse.
#### Repetition: The model occasionally repeated phrases, which I mitigated by using a repetition penalty.
By systematically adjusting these parameters and refining the dataset, I achieved better quality and coherence in the generated text.


![Screenshot 2024-10-18 015951](https://github.com/user-attachments/assets/7670ee50-c4e0-412a-b2dc-b56e3cfa83c5)
![Screenshot 2024-10-18 020014](https://github.com/user-attachments/assets/d0275bf7-2d63-42c5-86fd-3b54c63b5f2b)

## Tokenization and Its Role:
Tokenization is the process of breaking down raw text into smaller components (subwords or tokens) that GPT-2 can process. Each token is mapped to an integer ID, and the model processes sequences of these tokens during training and generation. Tokenization plays a critical role in ensuring that the model can learn from and generate human-readable text efficiently. In this task, the tokenizer handled complex vocabulary by using subword units, allowing the model to better handle out-of-vocabulary words or novel terms during both training and generation.

Overall, this project helped me understand how essential components—like tokenization, hyperparameter tuning, and training strategies—work together to achieve high-quality text generation.

