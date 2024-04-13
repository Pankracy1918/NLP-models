The file fine_tuning_roberta_squad_qa is a python file in which I was experimenting with best fine tuning method and model in order to fine tune bert based model on question answering task. The results in accuracy were very satisfying, the accuracy was 0.95 on only first epoch!

The file fine_tuning_bert_squas_wa was is a attempt to fine tune bert base on question answering task, but the accuracy was very low 0.65 on first epoch. After training it and transmission of weights the accuracy raised to 0.73.

Both models were fine tuned on squad dataset v.2.0.

The file gemma-generation I approach the problem of data generation on LLMs. I use gemma-2b-it as language model and 1300-towards-datascience-medium-articles-datase as dataset. I tried diffrent prompt and pipeline approaches, but the choosen one was optimal to the quality of questions. The form of file extension (txt) was choosen because there was a problem with kaggle computational cloud storage and there was a possibility that all question will be deleted due to error of internet browser lack of ram usage.
