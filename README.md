# codon2vec :white_flower:
Vector representations of codons, can be used to optimize RNN learning tasks.

Method see: https://code.google.com/archive/p/word2vec/

Trained on codon table (raw_input.txt) with hierachical softmax.

```
word2vec -train data/codons.txt -output codon.txt -size 50 -window 1 -sample 1e-5 -threads 4 -min-count 1 -binary 0 -save-vocab codon_vocab -hs 1
```
