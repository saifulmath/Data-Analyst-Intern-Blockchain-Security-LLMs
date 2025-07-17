📘 Internship Report: Analyzing Smart Contract Exploits or Other Security Incidents with LLMs

🔍 Overview
This repository contains the final internship report authored by Mohd Saiful Islam, as part of the Applied Mathematics in Networking and Data Science program at Hochschule Mittweida.

The internship focuses on applying Large Language Models (LLMs) — specifically the Meta LLaMA-3-8B-Instruct model — to analyze and detect vulnerabilities in Ethereum smart contracts. The core contribution lies in evaluating and comparing baseline and Retrieval-Augmented Generation (RAG)-enhanced LLMs to detect reentrancy attacks, one of the most critical threats in decentralized finance (DeFi).

📄 Report Summary
1) LLM Used: Meta LLaMA-3-8B-Instruct

2) Dataset: 40 Solidity smart contracts (20 vulnerable, 20 secure)

3) Vulnerability Focus: Reentrancy attacks (single-function & cross-function)

4) Methodologies:

   I. Prompt engineering

   II. Structured evaluation

   III. Vector-based semantic retrieval using FAISS

5) Evaluation Metrics: Accuracy, Precision, Recall, F1 Score,  Specificity, FPR, FNR

6) Tools: Hugging Face Transformers, SentenceTransformers, FAISS, Google Colab Pro, Pytorch
7) Programming Language: Python, Solidity


📊 Key Findings
   | Metric    | LLaMA (Base) | RAG-LLaMA (Enhanced) |
| --------- | ------------ | -------------------- |
| Accuracy  | 87.55%       | 98.50%               |
| Precision | 89.57%       | 97.09%               |
| Recall    | 85.00%       | **100.00%**          |
| F1 Score  | 87.22%       | 98.52%               |
| Specificity| 90.10%      | 97.00%               |
| FNR       | 15.00%       | **0.00%**            |
| FPR       | 9.90%        | 3.00%                |

The RAG-enhanced model achieved perfect recall, eliminating all false negatives, which is critical for vulnerability detection in security-sensitive environments.

📫 Contact
Author: Mohd Saiful Islam

Internship Position: Data Analyst Intern – Blockchain Security & LLMs

University: Hochschule Mittweida

Supervisors:

I. Prof. Dr.-Ing. Alexander Lampe (University)

II. Dipl. Volkswirt, Dipl. Kfm. Mario Oettler (BCCM)
