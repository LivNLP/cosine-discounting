# Mitigate-the-impact-of-word-frequency-on-under-and-over-cosine-similarity-estimation-of-BERT

## research paper
- In process of the 61st annual meeting of the Association for Computational Linguistics, 2023
- [Link to the paper](https://drive.google.com/drive/folders/1HYjiehgEu6hsl-36NmfRJXuGlUwmLeYv?usp=sharing)

## oblectives:
- Investigate the impact of word frequency on BERT’s properties including isotropy,
self-similarity, and l2-norm to understand why low and high-frequency words cause
improper estimation of cosine similarity.
- Mitigate the impact of word frequency on cosine similarity estimation without
decreasing the accuracy of the BERT baseline.

## part 1: data collection
- word embedding and BERT properties collection
- distributions of words

## part 2: relationships between word frequency and BERT's properties
- word frequency VS local l2-norm
- word frequency VS global l2-norm
- word frequency VS l2-norm variance
- word frequency VS global isotropy
- word frequency VS global self-similarity

## part3: approaches to mitigate the impact of word frequency on under and over cosine similarity estimation of BERT
- BERT baseline
- approach1: a single linear adjustment
- approach2: two-way linear adjustment
- approach3: word type-dependent adjustment
- approach4: probabilistic word type-dependent adjustment
- approach5: z-score normalization

Note that version 1 is for the University of Liverpool thesis and version 2 is for publication.
