# Inside Out 2: Make Room for New Emotions & LLM

This repository contains the code files and results of a reproducibility study revisiting the Inside Out framework introduced by [Landoni et al.](https://dl.acm.org/doi/abs/10.1145/3340631.3394847). All personal data including queries procured from the user study conducted in the original study as well as IAS responses have been due to ethical considerations.

## Synthetic Log Generation
To create a synthetic log, first create a csv file containing all the user queries. The csv file should contain the following coloumns:

1. QID: The unique query ID
2. Query: The query formulated by the child
3. Prompt Type: The type of prompt (General or Emotionally Charged in this study) given to the child to formulate a query
4. Task Sentiment: The sentiment category assigned to an search task (Positive or Negative, in this study)

