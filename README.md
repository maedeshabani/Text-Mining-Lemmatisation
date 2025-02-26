# Text-Mining-Lemmatisation
## Overview
Welcome to the Text-Mining-Lemmatisation project! This repository is the culmination of our collaborative efforts to develop a French lemmatizer for the Text-mining & Chatbots course, under the guidance of Professor Thomas Gerald at Paris-Saclay University. Our primary objective was to explore various strategies for lemmatizing French text, thereby enhancing text mining and natural language processing tasks.

## Approaches
We employed three distinct methodologies to achieve effective lemmatization:

- **Dictionary-Based Approach**: Utilizing a predefined dictionary, this method maps words to their base forms, ensuring accurate lemmatization based on existing lexical resources.

- **Machine Learning Approach**: Leveraging the capabilities of Scikit-learn and Keras, we developed and trained models that learn lemmatization patterns from annotated datasets, enabling the system to generalize to unseen words.

- **Comparison with Pretrained Tools**: To benchmark our approaches, we evaluated the performance of our methods against spaCy, a renowned natural language processing library equipped with pretrained lemmatization tools.

## Repository Structure
The repository is organized as follows:

├── Final_lemmatization.ipynb: A comprehensive Jupyter Notebook detailing the implementation of all three approaches, including code, explanations, and results.

├── TextMining_ParisSaclay2025.pdf: The final report documenting our methodologies, experiments, results, and insights gained throughout the project.

├── README.md: This file, providing an overview and guide to the repository.

## Getting Started
To explore and utilize the lemmatizer, follow these steps:

1. Clone the repository:
   ```sh
   git clone https://github.com/maedeshabani/Text-Mining-Lemmatisation.git
   cd Text-Mining-Lemmatisation
   
2. Run the Notebook: Launch Jupyter Notebook and open Final_lemmatization.ipynb to delve into the code and execute the lemmatization approaches.

## Results and Insights
Our experiments revealed that while the dictionary-based approach offers precision for known words, the machine learning models demonstrated superior adaptability to novel terms. Comparing our methods with spaCy's pretrained tools provided valuable benchmarks, highlighting the strengths and areas for improvement in our approaches.

## Contributors
Maede Shabani Samgh Abadi: M2 Data Science, Université Paris-Saclay

Negin Heidarifard: M2 Artificial Intelligence, Université Paris-Saclay

Mennaallah Khaled Abdou Salim: M2 Internet of Things, Université Paris-Saclay

## License
This project is licensed under the MIT License.

We invite you to explore our work, provide feedback, and contribute to the ongoing development of effective lemmatization techniques for the French language.
