# Debate Decoder: Unveiling Key Parliamentary Themes

## Overview
This project leverages **Latent Dirichlet Allocation (LDA)** topic modelling to analyze debates from the Canadian House of Commons. By extracting key topics such as housing, Indigenous support, and military justice, this project provides actionable insights for policymakers, advocacy groups, and the public. Interactive visualizations allow stakeholders to explore the themes driving parliamentary discussions, promoting transparency and informed decision-making.

## Features
- **Topic Modeling with LDA**: Extracts key themes from parliamentary discussions.
- **Interactive Visualization**: Uses pyLDAvis to explore topics and their relevance intuitively.
- **Data Preprocessing**: Removes noise through tokenization, stops word removal, and prevents lemmatization.
- **Quantitative Insights**: Analyzes topic distribution and coherence for meaningful results.

## Tools & Technologies
- **Programming Language**: Python
- **Libraries**: 
  - `pandas` for data manipulation and cleaning
  - `NLTK` for text preprocessing
  - `Gensim` for LDA modeling
  - `pyLDAvis` for interactive topic visualization
- **Development Environment**: Jupyter Notebook

## Dataset
The dataset consists of parliamentary debates sourced from the **Hansard transcripts** of the Canadian House of Commons. Preprocessing steps include removing stop words, punctuation, and irrelevant metadata to enhance the model’s interpretability.

## Results
- Identified **seven distinct topics**, including:
  1. **Citizenship and Legal Rights**
  2. **Community and Indigenous Support**
  3. **Housing and Economic Policy**
  4. **Quebec and Bloc Québécois**
  5. **Parliamentary Procedures and Housing**
  6. **Military Justice and Sexual Misconduct**
  7. **Provincial Support and Social Issues**
- Achieved a **coherence score of 0.49**, indicating interpretable and meaningful topics.
- Visualized topics using an **Intertopic Distance Map** for better stakeholder interaction.
