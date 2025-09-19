# 🐍 Python Code Generator  

[![Made with Python](https://img.shields.io/badge/Python-3.9%2B-yellow?logo=python)](https://www.python.org/)  
[![Model](https://img.shields.io/badge/Model-CodeT5--base-green?logo=transformers)](https://huggingface.co/Salesforce/codeT5-base)  
[![LoRA](https://img.shields.io/badge/LoRA-Enabled-purple)](https://arxiv.org/abs/2106.09685)  
[![Evaluation](https://img.shields.io/badge/Eval%20Loss-0.37-success)]()  
[![Status](https://img.shields.io/badge/Project-Completed-brightgreen)]()  
[![Stars](https://img.shields.io/github/stars/YOUR_USERNAME/YOUR_REPO?style=social)]()  

🌟 This project was developed as part of the **Generative AI Summer Training 2025** organized by **APPLAI – Ain Shams University**, where it proudly achieved **third place 🥉** in the projects contest.  

---

## 🚀 Project Overview
The **Python Code Generator** is a system that translates **natural language problem statements** into **executable Python functions**.  
It leverages **Generative AI** techniques to bridge the gap between human language and programming, making coding faster and more accessible.  

---

## 🔧 Techniques Applied  

- 🧹 **Data Preprocessing**
  - Validated code with `ast.parse`.
  - Fixed structure using `parso` & `black`.
  - Removed non-ASCII characters.
  - Preserved only valid programming/math symbols.

- 🏗 **Preserving Code Structure**
  - Avoided stemming/lemmatization to maintain syntax integrity.

- 🧠 **Model Training**
  - Fine-tuned **Salesforce/CodeT5-base** with **LoRA** for efficient training.

- ✅ **Evaluation**
  - Tested with **zero-shot**, **one-shot**, and **few-shot** prompts.
  - Example tasks: Fibonacci sequence, reverse string, addition, multiplication, odd/even detection.

---

## 📊 Results  

| Metric       | Value |
|--------------|-------|
| Eval Loss    | **0.37** |
| Epochs       | **3** |
| Code Validity| **100% syntactically correct** |
| Tasks Passed | **Fibonacci, String Ops, Math Ops, Odd/Even** |

---

## ✨ Key Features  

- 📝 Converts natural language into runnable Python functions.  
- ⚡ Supports multiple problem types (math, strings, logic).  
- 🔌 Uses LoRA for efficient fine-tuning of large models.  
- 🖥️ Trained on curated & validated code dataset.  

---

## 🙏 Acknowledgements  
Special thanks to the **APPLAI community** for providing a supportive learning and innovation environment.  

---

## 📌 Future Work  

- 🌍 Expand to support **multi-language code generation** (C++, Java).  
- 🧪 Enhance with **unit test auto-generation**.  
- 🌐 Deploy as an **interactive web app** for non-technical users.  

---

## 🏷️ Keywords  
`Generative AI` · `NLP` · `Python` · `LoRA` · `CodeT5` · `Code Generation` · `Machine Learning`  

