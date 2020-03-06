# NLP Engineer Internship Test

## Objective

- Make an intent classifier with the dataset provided in the repository in which the imput will be a phrase and the model must correctly classify it in one of the intentions defined in the dataset
- The main objective of the test is to assess the candidate's ability to solve problems and demonstrate his attempts, hypotheses, solutions clearly and the ability to analyze data, extract information, suggest conclusions, and support decision-making.

### Example interaction with the resulting model
Just a demonstrative example to understand the problem, the output can be formatted according to the candidate's preference so that it shows the intention and the confidence that the model returned
```
example 1:
input: como ocorre a transferência de processos para o SEI?
output: 
intent: processos_administrativos 
confidence: 96.7%

example 2:
input: quais são os documentos disponíveis?
output: 
intent: documentação
confidence: 83.2%
```

## Requirements
- Put all the code, logic, hypotheses, etc. organized in the jupyter notebook of the repository (i.e. specific actions you would take based on your analysis) and methodology.

## Information about the datasets

The dataset is in the dataset.txt file in the repository, it is in the format:

```
intent:intent_name1
-sentence1
-sentence2
...
-sentenceN

intent:intent_name2
-sentence1
-sentence2
...
-sentenceN

...
```

Tip: it is interesting to put your different approaches and attempts in the notebook to support decision making<br/>
Have fun!
