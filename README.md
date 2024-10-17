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
