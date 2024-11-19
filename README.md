# Modelo de Classificação de Categorias de Frases Predicativas

Este repositório contém a implementação de um modelo para classificação de frases predicativas em categorias específicas, buscando identificar padrões de linguagem associados a diferentes aspectos de gênero e conotação.

## Objetivo

O objetivo do projeto é classificar frases predicativas em uma das seguintes categorias:

- **Aparência**: Adjetivos relacionados a características físicas ou estéticas.
- **Sexual**: Adjetivos com conotação sexual ou hipersexualização.
- **Papel Social**: Adjetivos que remetem a funções, status ou papéis atribuídos socialmente.
- **Caráter**: Adjetivos que refletem traços de personalidade ou moral.
- **Emoção**: Adjetivos que expressam sentimentos ou estados emocionais.
- **Neutro**: Adjetivos que não se enquadram nas categorias acima.

## Estrutura do Repositório

### Arquivos principais

1. **`correspondencias.ipynb`**  
   Este notebook contém o código para procurar correspondências entre um conjunto de mil adjetivos previamente anotados e um dataset de frases. A análise auxilia na identificação de padrões de frequência e categorias.

2. **`categorização.ipynb`**  
   Este notebook implementa o modelo de categorização utilizando o **BERTimbau**, incluindo etapas de pré-processamento, extração de embeddings e classificação das frases nas categorias definidas.

## Tecnologias Utilizadas

- **Linguagem**: Python  
- **Modelo pré-treinado**: [BERTimbau](https://github.com/neuralmind-ai/portuguese-bert)  
  Utilizado para extrair representações semânticas robustas de frases em português.
- **Bibliotecas principais**:
  - Hugging Face Transformers para o uso do BERTimbau
  - SpaCy para análise de linguagem natural
  - Pandas e NumPy para manipulação de dados

## Como Usar

1. **Clone o repositório:**
   ```bash
   git clone https://github.com/firminovitoria/profissoes-categorias.git
   cd profissoes-categorias
