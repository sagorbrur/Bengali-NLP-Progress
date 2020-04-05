Named entity recognition (NER) is the task of tagging entities in text with their corresponding type.
Approaches typically use BIO notation, which differentiates the beginning (B) and the inside (I) of entities.
O is used for non-entity tokens.

Example:

| Mark | Watney | visited | Mars |
| --- | ---| --- | --- |
| B-PER | I-PER | O | B-LOC |


| Model           | Accuracy  |  Paper / Source | Code | Datasets|
| ------------- | :-----:| --- | --- | --- |
| SVM (Asif et al. 2008) | 91.8 | [Bengali Named Entity Recognition using Support Vector Machine](https://www.aclweb.org/anthology/I08-5008.pdf) | --- | --- |
