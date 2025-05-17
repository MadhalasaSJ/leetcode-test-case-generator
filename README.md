# LeetCode Test Case Generator

This project automates the generation of unit test cases for LeetCode-style problems using pre-trained transformer models (e.g., T5-small). It is designed to help developers, educators, and interviewers generate edge-case examples for common algorithm questions like "Two Sum", "Add Two Numbers", "Longest Substring Without Repeating Characters", and more.

## 🚀 Features

- Uses **T5-small** model from Hugging Face for test case generation.
- Generates input-output pairs for various coding challenges.
- Can be extended to support custom prompts and additional problems.
- Output results stored in [`results.md`](./results.md)

## 🛠️ Tech Stack

- Python
- Hugging Face Transformers
- Jupyter Notebook

## ✅ How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/YourUsername/leetcode-test-case-generator.git
   cd leetcode-test-case-generator

2. Install requirements:
   ```bash
   pip install -r requirements.txt
3. Open and run the notebook:
  jupyter notebook Leetcode_test_case_generation (1).ipynb

# 📂 Outputs
Generated test cases are saved in results.md   


