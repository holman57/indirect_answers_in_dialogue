Understanding Indirect Answers in Dialogue Systems - Inferring direct answers from indirect answers to questions. 

A reproduction of the results and experiments carried out by Louis et al (2020) 

Louis, A., Roth, D. and Radlinski, F., 2020. "I'd rather just go to bed": Understanding Indirect Answers. [online] arXiv.org. Available at: <https://arxiv.org/abs/2010.03450> . 


Consists of the following experiments done on :
BERT - YN (Question Only) 
BERT - YN (Answer Only)
BERT (Question + Answer)
BERT BOOLq - YN
BERT MNLI - YN
BERT DIS - YN

Folders:
BERT - Consists of all the above mentioned experiments in different ipynb files
Results - Results of the above models  
    - Basic Error analysis code
Data: Circa, BOOLq, MNLI and DIS datasets [data files not included in this repository due to size constraints]

Available here:

Circa: https://github.com/google-research-datasets/circa
Boolq: https://github.com/google-research-datasets/boolean-questions
MNLI: https://cims.nyu.edu/~sbowman/multinli/
DIS: https://github.com/ekQ/discourse-connectives

Other Files:
DataSplit.ipynb - Writes the data files to DL Project/Data folder
baselineAttempt#1_MATCHED - Makes and evaluates the majority baseline


