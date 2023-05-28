# NLPexercise3
In this exercise, we performed various tasks related to natural language processing (NLP) using a provided training code by the teacher. The tasks included code execution and performance reporting, model evaluation and new sentence input, explanation of the align_label function, code modifications such as freezing BERT weights, merging training and validation sets, performing POS tagging, carrying out text chunking, and using the roberta-base pre-trained model.

In the last two tasks, we utilized a generative pre-trained language model called ChatGPT, which is based on Transformers. With ChatGPT, we performed the tasks of named entity recognition (NER), POS tagging, and text chunking using both zero-shot and few-shot prompting approaches. The detailed analyses, results, and code modifications for each task can be found in the corresponding files.

## Task 1: Code execution and performance report

We ran the initial code and reported its performance (accuracy and macro-average accuracy) on the test set. You can find these results in the file Question1_2_3.

## Task 2: Model Evaluation and New Sentence Input

We selected a sentence from the test set with at least 10 tokens where the model fails to find the correct tags for some tokens. We also fed a new sentence into the final model and showed the tokens for which the model makes the correct and incorrect prediction. You can refer to the file Question1_2_3 for the detailed analysis and results.

## Task 3: Explanation of align_label Function

We explained the exact role of the align_label function and why it sets the ids of some tokens to the value -100. The explanation can be found in the file Question1_2_3.

## Task 4: Freezing BERT Weights

We modified the original code to freeze the weights concerning the pre-trained language model BERT. You can check the modifications and the performance comparison with the original model in the file Question_4.

## Task 5: Merging Training and Validation Sets

We adjusted the original code to use the union of the training set and the validation set (17,291 sentences) as the training set. The code modifications and performance comparison with the original model are in the file Question_5.

## Task 6:  POS Tagging

We altered the original code to perform POS tagging instead of NER. You can find the changes and the results in the file Question_6.

## Task 7: Text Chunking

We modified the original code to carry out text chunking instead of NER. You can find the changes and the results in the file Question_7.

## Task 8:  Using Roberta-base

We altered the original code to use the roberta-base pre-trained model (and the corresponding tokenizer). You can find the changes and the results in the file Question_8.

# Task 9 and 10
In the last two tasks, we used a generative pre-trained language model based on Transformers (Generative Pre-trained Transformer), ChatGPT, to perform the tasks of NER, POS tagging, and Chunking.

## Task 9: Zero-shot Prompting using ChatGPT

We repeated the second task for all 3 tasks (NER, POS tagging, Chunking) using ChatGPT with zero-shot prompting. Refer to the file Question_9 for the detailed prompt and evaluation.

## Task 10: Few-shot Prompting using ChatGPT

We repeated the second task for all 3 tasks (NER, POS tagging, Chunking) using ChatGPT with few-shot prompting. Refer to the file Question_10 for the detailed prompt and evaluation.
