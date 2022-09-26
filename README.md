# document-similarity

## Introduction

This is the repository for the paper titled "Legal Case Document Similarity: You Need Both Network and Text" accepted at the <a href="https://www.sciencedirect.com/science/article/pii/S0306457322001716">Information Processing and Management Journal</a>.

The task here is to calculate a similarity score (in the range 0-1) between two case documents. We provide the validation and test set documents for the task.

## Citation
If you use this dataset, please refer to the following paper:
```
@article{bhattacharya-ipm22,
title = {Legal case document similarity: You need both network and text},
author = {Paheli Bhattacharya and Kripabandhu Ghosh and Arindam Pal and Saptarshi Ghosh},
journal = {Information Processing \& Management},
volume = {59},
number = {6},
pages = {103069},
year = {2022},
issn = {0306-4573},
doi = {https://doi.org/10.1016/j.ipm.2022.103069},
}
```
## Data Format

The validation.zip folder contains the validation dataset. The test.zip folder contains the test dataset.

In each dataset, there is:

(a) A "documents" folder : contains the full text of the documents.

(b) similarity_scores.csv : file containing the legal expert assigned similarity score between two documents, in the format 
```
doc1,doc2,score
```

A document is identified by its filename in the similarity_scores.csv file.

For instance, a pair in the similarity_scores file : 1971_138,1992_47,0.77 from the validation dataset.

The document 1971_138 can be found in validation/documents/1971_138.txt & 1992_47 can be found in validation/documents/1992_47.txt


