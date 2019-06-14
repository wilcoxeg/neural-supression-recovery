# Neural Supression & Recovery

This repo contains the data for *Hierarchical Representation in Neural Language Models: Suppression and Recovery of Expectations* by Ethan Wilcox, Roger Levy and Richard Futrell, presented at BlackboxNLP 2019.

Each directory contains experimental items (*input.txt*) and models' word-by-word surprisals (*model-name_output.tsv*). The word-by-word surprisal files have the following format:
```
token1 0.0
token2 ...
.      ...
<eos>  0.0
```
where the second column (separated by `\t`) gives the surprisal in bits of the token.

### Center Embeddings

Contains the experimental items and model surprisals for the results presented in Section 3 of the paper.

### Filler-Gap Dependencies

Contains the experimental items and model surprisals for the results presented in Section 4 of the paper. 