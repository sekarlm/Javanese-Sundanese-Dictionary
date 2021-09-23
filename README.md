<p align="center">
  <h2 align="center">Javanese and Sundanese Dictionary</h2>
</p>

## Introduction
Bilingual dictionary induction (BDI) is one of the research in NLPfield which aims to produce pair translation from two differentlanguages. BDI needs parallel and comparable corpora to producepair translations. Javanese and Sundanese are low-resourceslanguages. It is difficult to collect parallel and comparable corporafrom low-resource languages. The available data for those languagesare monolingual corpora. We used cross-lingual embeddingproduced from monolingual corpora to retrieve the pair translations.We produced cross-lingual embedding using pseudo-bilingualcorpora and monolingual mapping approaches. Then, the Nearestneighbors(NN) and the cross-domain local scaling (CSLS) methodused to retrieve translation pair of Javanese and Sundanese.

## General Architecture Design
<p align="center">
    <img src="contents/arsitektur umum fix.png" alt="Model Architecture" height="auto">
</p>

The proposed solution of bilingual dictionary induction for Javanese and Sundanese consists of four main processes. 
1. First, preprocessed the train and test data. 
2. Then, generate word embedding from language corpus using Word2Vec, FastText, and Feature Extraction Multilingual BERT. 
3. After that, generate cross-lingual embedding of Javanese toward Sundanese. Cross-lingual embedding generated using pseudo-bilingual corpora and monolingual mapping. 
4. Last, retrieve pair translation retrieval of Javanese and Sundanese words. 

## Implementation
- [Pseudo-bilingual Corpora](https://github.com/sekarlm/Pseudo-Bilingual-Corpora)
- [Monolingual Mapping](https://github.com/sekarlm/MUSE-for-Monolingual-Mapping/blob/master/README.md)
