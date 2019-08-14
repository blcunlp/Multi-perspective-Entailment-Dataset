# Multi-perspective-Entailment-Dataset

## Description


## Data

The Annotated Multi-perspective Entailment Dataset can be downloaded at [here](https://)

Each line in the excel file corresponds to an instance, and it is arranged as：  
>premise hypothesis 4-category-labels entailment-label 4-model-labels.

### 4-category-labels

The kind of 4-category-labels can be clearly seen in the following table:

|category |annotated lable| sub-category |annotated lable|
|:-:|:-:|:-:|:-:|
| CR(Commonsense Reasoning)         | A  |EmoR(Emotion Reasoning)      | A1 |
|  |  |QR(Quantities Reasoning)     | A2 |
|  |  |SR(Spatial Reasoning)        | A3 |
|  |  |EveR(Event Reasoning)        | A4 |
| LP(Lexical and Phrasal Level)     | B	|Hyp(Hypernymy)               |	B1 |
|  | 	|Syn(Synonymy)                | B2 |
|  |  |Mer(Meronymy)	              | B3 |
| SS(Syntactic Structure)           | C |Elli(Ellipsis)               | C1 |
|  |  |Ext(Extraction)              | C2 |
|  |  |ST(Syntactic Transformations)| C3 |
| Diacard                           | D  |                            |    |

From three levels, we divide the entailment types into three categories. Data without classification significance are given an "Diacard" label. There are also ten sub-categories under the three categories, which are represented numerically.

The categories and sub-categories are not independent. When an instance has two sub-category labels, they are marked with "A/B/C-complex", abbreviated to "A/B/C-com".

### entailment-label
Our data comes from the entailment data of SNLI test set, so the "entailment-label" at file is shown as "True".

### 4-model-labels
