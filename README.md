# Verbesserung von Belohnungsmodellen durch adversariale Trigger-Generierung
**Enhancing Reward Models through Adversarial Trigger Generation**

## Overview
This repository contains the resources and code for the research paper:  
**"Verbesserung von Belohnungsmodellen durch adversariale Trigger-Generierung"**  
*Enhancing Reward Models through Adversarial Trigger Generation*  

The research explores methodologies for generating adversarial triggers to identify and improve weaknesses in reward models. The goal is to enhance the robustness of generative AI systems by minimizing reward scores through targeted adversarial inputs.

## Abstract
This paper describes the development and evaluation of a methodology for generating adversarial triggers for reward models. The proposed approach combines token embedding analysis and random search techniques to identify universal triggers that minimize reward scores. The effectiveness of this approach is demonstrated through comprehensive experiments using LLama models and curated datasets.

---

## Repository Contents
- `code/`: Contains the Python scripts for trigger generation and evaluation.
- `data/`: Sample datasets used for the experiments.
- `results/`: Output logs and evaluation metrics.
- `Verbesserung_von_Belohnungsmodellen_durch_adversariale_Trigger_Generierung.pdf`: Full PDF version of the paper.

---

## Key Features
- **Token Embedding Analysis:** Identifies critical token differences across reward models.
- **Random Search Optimization:** Generates adversarial triggers through iterative token replacements.
- **LLama Model Evaluation:** Validates the methodology on pre-trained generative models.

---

## How to Use
### 1. Setup
Ensure you have Python installed along with the necessary dependencies.  
Run the following command to install dependencies:
```bash
pip install -r requirements.txt
