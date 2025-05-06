# Improving LLM Classification Performance with Data Balancing

This repository builds upon the work of [Tommi Buder-Gröndahl](https://github.com/tombgro/llm-workshop) and extends the original LLM classification pipeline by applying **data balancing techniques** such as **oversampling** and **undersampling**.

## What’s New

The original notebook [`llm-workshop_original.ipynb`](llm-workshop_original.ipynb) serves as the baseline. In the extended version [`llm-workshop.ipynb`](llm-workshop.ipynb), I demonstrate how addressing class imbalance in the dataset significantly improves the **reliability and performance** of Large Language Model-based classifiers.

### Key Enhancements

- Applied **oversampling** and **undersampling** to balance class distribution.
- Demonstrated **improved model performance** through evaluation metrics.

## Repository Structure
```text
├── README.md                   # Project documentation (you’re here!)
├── llm-workshop_original.ipynb # Original notebook from Tommi Buder-Gröndahl
├── llm-workshop.ipynb          # Improved version with data balancing
└── spamdata_vs.csv             # Dataset used for training and evaluation
      
