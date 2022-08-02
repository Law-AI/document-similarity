# document-similarity

## Introduction

This is the repository for the paper titled "Legal Case Document Similarity: You Need Both Network and Text" which is under minor revision at the Information Processing and Management Journal.

The task here is to calculate a similarity score (in the range 0-1) between two case documents. We provide the validation and test set documents for the task.

## Data Format

The validation.zip folder contains the validation dataset. The test.zip folder contains the test dataset.

In each dataset, there is:
-(a) A "documents" folder : contains the full text of the documents.
- (b) similarity_scores.csv : file containing the legal expert assigned similarity score between two documents, in the format <doc1>,<doc2>,<score>
- A document is identified by its filename in the similarity_scores.csv file.
- For instance, a pair in the similarity_scores file : 1971_138,1992_47,0.77 from the validation dataset.
- The document 1971_138 can be found in validation/documents/1971_138.txt & 1992_47 can be found in validation/documents/1992_47.txt


