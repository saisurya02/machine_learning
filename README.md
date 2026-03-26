# Transformer Input Length Effects

## Project Description

This project explores how input length influences the performance of Transformer-based models in natural language processing tasks. Transformer models operate with a fixed maximum number of tokens, which means longer inputs must be truncated. This study examines how such truncation affects predictive accuracy, information retention, and computational efficiency.

Using a lightweight BERT model and a text classification dataset, the project systematically varies the maximum input length and evaluates its impact on model behaviour. The goal is to provide both theoretical insight and practical understanding of how context length affects learning and performance.

---

## Approach

The experiment is designed to isolate the effect of input length by keeping all other factors constant. The model is trained and evaluated multiple times with different maximum token limits, allowing direct comparison of performance and efficiency.

Several key aspects are analysed:

* how much information is lost due to truncation
* how model accuracy changes with increasing context
* how computational cost grows with longer sequences

---

## Key Findings

The results demonstrate a clear trade-off between context and efficiency. Short input lengths lead to significant truncation and loss of information, which limits model performance. Increasing the input length reduces truncation and improves accuracy, but also increases runtime.

Interestingly, intermediate input lengths do not always produce the best results, highlighting that performance depends not only on context size but also on how effectively the model can utilise that context.

---

## Repository Structure

This repository contains all materials required to reproduce the experiment and results. The notebook includes data processing, model training, evaluation, and visualization steps. Generated figures illustrate the relationship between input length, performance, and computational cost.

---

## Reproducibility

All experiments can be reproduced by running the notebook in a standard Python environment. The required dependencies are listed in the repository, and the dataset is automatically downloaded when the notebook is executed.

---

## Accessibility

This project has been designed with accessibility in mind. Visualizations use clear labels, readable font sizes, and distinct line styles to ensure they are interpretable without relying solely on colour. Descriptive explanations accompany all figures to support understanding for a wide range of users.

---

## License

This project is provided for educational use. Please refer to the license file for details on reuse and distribution.
