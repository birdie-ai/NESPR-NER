# NESPR-NER
Repository for "On Extracting Overlapping Named Entities from E-Commerce Product Reviews"


## Abstract
E-commerces such as Amazon, E-bay and many others receive from consumers thousands of product reviews every day with rich fine-grained information that, without the aid of Opinion Mining, would be impossible to make sense of. Common tasks in this domain, such as Aspect-Based Sentiment Analysis, Taxonomy Learning and Entity Linking, depend on extracting relevant entities from text with considerable performance. In this paper, we propose a set of entities that provides specific structuring for product reviews in order to enable richer insights for this domain. We also provide a new dataset on laptop reviews annotated with overlapping entities that is used to experiment with state-of-the-art named entity recognition models. Lastly, we perform experiments to understand if this approach generalizes well across different product categories. 

## Results
Obtained through 5 x 2-fold cross validation. 
[Download Trained Model](https://drive.google.com/file/d/1XhfFrLZy2TfvEh8RDAWDTrgUhmIpGNWs/view?usp=sharing)
|            | Precision | Recall | F1-Score |
| :--------: | :-------: | :----: | :------: |
|    ATTR    |   0.52    |  0.54  |   0.53   |
|   BRAND    |   0.64    |  0.68  |   0.66   |
|  POS_EXP   |   0.19    |  0.15  |   0.17   |
|   ISSUE    |   0.18    |  0.13  |   0.15   |
|  PRODUCT   |   0.50    |  0.59  |   0.54   |
|  RETAILER  |   0.62    |  0.62  |   0.61   |
|   PERSON   |   0.53    |  0.43  |   0.47   |
| CONTXT_USE |   0.40    |  0.35  |   0.37   |


## Citing
TBA