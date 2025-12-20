# Kashmiri News Domain Dataset and Experiments Code

## Overview
This repository provides the **Kashmiri News Domain Dataset** along with experimental code for benchmarking natural language processing (NLP) models on **low-resource Kashmiri text classification**. The dataset consists of **15,036 manually refined Kashmiri news snippets**, each annotated with a domain label.

The repository also includes experimental scripts for preprocessing, tokenization, similarity analysis, and evaluation using classical, transformer-based, and large language models (LLMs), supporting reproducible research in Kashmiri NLP.

---

## Dataset Description
- **Language**: Kashmiri  
- **Script**: Perso–Arabic  
- **Total Samples**: 15,036 news snippets  
- **Domains (10)**:
  - Medical  
  - Politics  
  - Sports  
  - Tourism  
  - Education  
  - Art and Craft  
  - Environment  
  - Entertainment  
  - Technology  
  - Culture  

The dataset was created via translation of English news snippets into Kashmiri and subsequently **manually refined to ensure linguistic accuracy and domain relevance**.

---

## Dataset Format
The dataset is provided in **XLSX format** with the following columns:

| Column Name | Description |
|------------|-------------|
| `Kashmiri` | News snippet in Kashmiri |
| `Domain`   | Corresponding domain label |

---

## Experiments and Code
This repository includes code for the following experiments:

- Text preprocessing and normalization  
- Similarity analysis and BLEU score evaluation  
- Tokenizer comparison and analysis  
  - ParsBERT  
  - BLOOM  
  - Flan-T5  
- Fine-tuning and evaluation of models for Kashmiri news classification  

📁 **Experiment folder**:  
`Similarity_BLEU_Tokenizer_Experiments/`

---

## Applications
- Kashmiri news domain classification  
- Low-resource language benchmarking  
- Tokenizer and model comparison for Perso–Arabic scripts  
- Transformer- and LLM-based text classification  

---

## Citation
If you use this dataset or code in your research, **please cite the following paper**:

> Deyar, D. U., Ramani, A., Gupta, D., Nair, P. C., & Venugopalan, M.  
> *Dataset creation and benchmarking for Kashmiri news snippet classification using fine-tuned transformer and LLM models in a low resource setting*.  
> **Scientific Reports**, 15, 40828 (2025).  
> https://doi.org/10.1038/s41598-025-24451-4

### BibTeX
```bibtex
@article{Deyar2025,
  title   = {Dataset creation and benchmarking for Kashmiri news snippet classification using fine-tuned transformer and LLM models in a low resource setting},
  author  = {Deyar, Deheem U. and Ramani, Anirud and Gupta, Deepa and Nair, Priyanka C. and Venugopalan, Manju},
  journal = {Scientific Reports},
  volume  = {15},
  number  = {1},
  pages   = {40828},
  year    = {2025},
  doi     = {10.1038/s41598-025-24451-4}
}
