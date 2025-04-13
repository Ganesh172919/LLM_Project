
# 🧠 LLM-based Health Assistance System

This project leverages a fine-tuned GPT-based language model to provide medical question-answering capabilities. It includes a dataset of health-related Q&A pairs, a Python notebook for fine-tuning, and a project report in PDF format.

## 📁 Project Structure

```
llm project/
│
├── Final data set for llm based health assitance (1).csv
├── LLM_finetuned_using_gpt_base_model.ipynb
└── LLM Project report.pdf
```

## 📄 File Descriptions

### 1. Final data set for llm based health assitance (1).csv
- **Description**: A medical Q&A dataset with over 16,000 entries.
- **Columns**: `question`, `answer`
- **Sample Entries**:
    - *What is (are) Glaucoma?*
    - *What causes Glaucoma?*
    - *What are the symptoms of Glaucoma?*

### 2. LLM_finetuned_using_gpt_base_model.ipynb
- **Description**: A Jupyter Notebook containing the code to fine-tune a GPT-based model (likely GPT-2) on the Q&A dataset.  
- **Lines of Code**: ~8,200 lines.

### 3. LLM Project report.pdf
- **Description**: A comprehensive report summarizing the project, including goals, methodology, model training, evaluation, and results.

## 🚀 How to Run

1. **Install Dependencies**:
   ```bash
   pip install transformers datasets torch
   ```

2. **Run Notebook**:
   - Open `LLM_finetuned_using_gpt_base_model.ipynb` in Jupyter or Google Colab.
   - Follow the cells to fine-tune and evaluate the model.

## 🧠 Use Case

This system is designed for use in medical assistant chatbots or health advisory tools where users can input natural language questions and receive accurate, medically informed answers.
