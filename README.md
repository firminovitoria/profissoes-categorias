
# Phrase Predicate Category Classification Model

This repository contains the implementation of a model for classifying predicate phrases into specific categories, aiming to identify language patterns associated with different aspects of gender and connotation.

## Objective

The objective of the project is to classify predicate phrases into one of the following categories:

- **Appearance**: Adjectives related to physical or aesthetic characteristics.  
- **Sexual**: Adjectives with sexual connotation or hypersexualization.  
- **Social Role**: Adjectives referring to functions, status, or socially assigned roles.  
- **Character**: Adjectives that reflect personality traits or moral qualities.  
- **Emotion**: Adjectives that express feelings or emotional states.  
- **Neutral**: Adjectives that do not fit into the categories above.

## Repository Structure

### Main Files

1. **`correspondencias.ipynb`**  
   This notebook contains the code to search for matches between a set of one thousand pre-annotated adjectives and a dataset of phrases. The analysis helps identify frequency patterns and categories.

2. **`categorização.ipynb`**  
   This notebook implements the categorization model using **BERTimbau**, including preprocessing steps, embedding extraction, and classification of phrases into the defined categories.

## Technologies Used

- **Language**: Python  
- **Pre-trained Model**: [BERTimbau](https://github.com/neuralmind-ai/portuguese-bert)  
  Used to extract robust semantic representations of Portuguese phrases.  
- **Main Libraries**:  
  - Hugging Face Transformers for using BERTimbau  
  - SpaCy for natural language analysis  
  - Pandas and NumPy for data manipulation

## How to Use

1. **Clone the repository:** 

   ```bash
   git clone https://github.com/firminovitoria/profissoes-categorias.git
   cd profissoes-categorias
