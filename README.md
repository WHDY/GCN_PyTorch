# GCN_PyTorch

A PyTorch implementation of "Semi-Supervised Classification with Graph Convolutional Networks " (ICLR 2017).

Some codes are referenced from https://github.com/tkipf/gcn and ***PyTorch Geometric***

## USAGE

Commands to run the code:

```commonlisp
python train.py --ds cora
```

```
python train.py --ds citeseer
```

```
python train.py --ds pubmed
```

## Others

- The code runs on CPU, but can be enabled to run on GPU by changing few lines easily.
- The calculation doesn't use the form of sparse matrix, so it takes a little bit longer to run the PubMed dataset.

