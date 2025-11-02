## ECE-7123 Deep Learning MIDTERM
# Gerneral
This repository is for NYU 2025 Fall Deep Learning course(ECE-7123) Midterm Miniproject.
The project is abput finetuning on Llama3-8b to predict if a given solution to a math problem is correct or not. Model will output True if the solution is correct, and False otherwise.

# Dataset
The dataset for this competition is the [Math Question Answer Verification Competition](https://huggingface.co/datasets/ad6398/nyu-dl-teach-maths-comp). It includes math problems from various topics and is structured into the following columns:

***question*** — The math question posed to the student.\
***answer*** — The ideal or correct answer to the question.\
***solution*** — A detailed reasoning or explanation that justifies the answer. Participants can use this to improve the model’s understanding of correctness.\
***is_correct*** — The target label indicating whether the provided answer is correct (True) or incorrect (False).

# Environment & Device

The project use ***Google Colab*** environments at newest version.\
The model is trained on A100 GPU provided by colab.


# Instruction
Follow the [notebook](https://github.com/LEILingShiYu/ECE-7123-DL-Midterm/blob/main/DLMid.ipynb) instruction to Train and Infer and save the model checkpoint & submission file on test dataset

# Related Resource
[Model checkpoint](https://drive.google.com/drive/folders/17FzCejuLutY7EfM34w2x2uLmbqxbVRhQ?usp=sharing)
