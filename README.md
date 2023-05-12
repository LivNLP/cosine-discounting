# Solving Cosine Similarity Underestimation between High Frequency Words by ℓ2 Norm Discounting

## research paper
- Proceedings of The 61st Annual Meeting of the Association for Computational Linguistics, Toronto, Canada, 2023
- [Link to the paper](https://drive.google.com/drive/folders/1HYjiehgEu6hsl-36NmfRJXuGlUwmLeYv?usp=sharing)

## oblectives:
- Investigate the impact of word frequency on cosine similarity of contextualized word embedding of masked language models such as BERT
- Mitigate the impact of word frequency on cosine similarity underestimation of contextualized word embedding in high-frequency words

## Publication
### 1. prepare BookCorpus: 
- download and save BookCorpus dataset

### 2. word embedding and BERT properties collection: 
- collect word embedding, word frequency, and l2-norm from the entire BookCorpus
 
### 3. word frequency VS l2_norm: 
- plots between word frequency and l2-norm

### 4. WIC preprocess:
- Process WiC by adding word frequency, default BERT cosine similarity, and BERT word embedding

### 5. parameters of the classifier:
- Bayesian optimization to find the theta of the classifier

### 6. WIC 5 cross validation dataset prep:
- Prepare 5 cross-validations dataset from WiC

### 7. l2_norm discounting:
- Cosine similarity prediction of the l2-norm discounting method compared to default BERT


## University of Liverpool thesis
### part 1: data collection
- word embedding and BERT properties collection
- distributions of words

### part 2: relationships between word frequency and BERT's properties
- word frequency VS local l2-norm
- word frequency VS global l2-norm
- word frequency VS l2-norm variance
- word frequency VS global isotropy
- word frequency VS global self-similarity

### part3: approaches to mitigate the impact of word frequency on under and over cosine similarity estimation of BERT
- BERT baseline
- approach1: a single linear adjustment
- approach2: two-way linear adjustment
- approach3: word type-dependent adjustment
- approach4: probabilistic word type-dependent adjustment
- approach5: z-score normalization
