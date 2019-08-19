# Multi-perspective-Entailment-Dataset

## Description


## Data

The Annotated Multi-perspective Entailment Dataset can be downloaded at [here](https://github.com/blcunlp/Multi-perspective-Entailment-Dataset/blob/master/Multi-perspective-Entailment-Dataset-CCL%E6%8F%90%E4%BA%A4%E6%95%B0%E6%8D%AE-final.xlsx)

Each line in the excel file corresponds to an instance, and it is arranged as：  
>Premise Hypothesis CR LP SS Discard.

**Premise** and **Hypothesis** are entailment sentence pairs. 

From three levels, we divide the entailment types into three categories——Commonsense Reasoning(**CR**), Lexical and Phrasal Level(**LP**), Syntactic Structure(**SS**). Data without classification significance are given an "**Diacard**" label. There are also ten sub-categories under the three categories, which are represented numerically.

The categories and sub-categories are not independent. When an instance has two sub-category labels, they are marked with "A/B/C-complex", abbreviated to "A/B/C-com".

The categories can be clearly seen in the following table:

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


