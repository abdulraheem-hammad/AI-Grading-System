# AI-Grading-System

Fine-tuning a LLaMA model to automatically evaluate and grade open-ended questions.

---

## Project Overview

This project focuses on fine-tuning the LLaMA large language model to automatically grade open-ended student answers. Unlike traditional grading systems that handle only multiple-choice or true/false questions, this system aims to evaluate free-form, written responses that require reasoning and understanding.

---

## Dataset Creation

The dataset was custom-created using AI tools to ensure diversity and quality:

- **GPT and Deepseek** created questions paired with answerss.


The resulting dataset contains a variety of questions designed to simulate real student responses for the model to learn grading.

---

## Methodology

- Used the **Unsloth** framework to fine-tune the LLaMA model on the custom dataset.
- Preprocessing steps were applied to format the dataset correctly for model training.
- The fine-tuned model aims to provide accurate grading and feedback on student answers, supporting educators with automated evaluation.

---

## Project Structure

- `AI-Grading-System.ipynb`: colab notebook containing the code for dataset preparation, model fine-tuning, and evaluation.
- `dataset_sample.csv`: A sample subset of the dataset with questions and answers.
- `README.md`: This file explaining the project.


---

## Tools & Technologies

- **Python** and **Google Colab**
- **LLaMA** large language model
- **Unsloth** fine-tuning framework
- **GPT** and **Deepseek** for dataset generation



---

## Usage

Run the notebook with dataset upoldaed to start traning
after traning you can use your own dataset for grading
---

## Notes

- This project was developed as my graduation project, exploring the application of large language models in educational assessment.


---

## Contact

For questions or collaboration, feel free to reach out!

---

*Thank you for checking out the AI-Grading-System project!*
