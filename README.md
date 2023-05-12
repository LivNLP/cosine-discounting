# Solving Cosine Similarity Underestimation between High Frequency Words by ℓ2 Norm Discounting

## research paper
- Proceedings of The 61st Annual Meeting of the Association for Computational Linguistics, Toronto, Canada, 2023
- [Link to the paper](https://drive.google.com/drive/folders/1HYjiehgEu6hsl-36NmfRJXuGlUwmLeYv?usp=sharing)

## oblectives:
- Investigate the impact of word frequency on BERT’s properties including isotropy,
self-similarity, and l2-norm to understand why low and high-frequency words cause
improper estimation of cosine similarity.
- Mitigate the impact of word frequency on cosine similarity estimation without
decreasing the accuracy of the BERT baseline.

## Publication

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
