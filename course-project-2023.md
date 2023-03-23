# Course project

To complete the course, successful completion of the project described here is required. The project affects grading as follows:

* Exam gives grades up to 4 with a minimally completed project (required to pass the course)
* Project completed with bonus task (see below) gives +1 to grade (up to 5 with exam)
* A _very_ well completed project with bonus task gives +2 to grade (up to 5 even with an exam giving grade 3)

## Basic project outline

The project involves creating a machine learning-based method for a text classification task of your choice. Specifically, you should

1. Select one of the text classification corpora below to work on. (If you'd prefer to suggest a corpus not listed here, get in touch with us on Discord!)
2. Read the paper presenting the corpus as well as any other relevant published materials about the corpus to assure you understand the data
3. Identify what is the state-of-the-art performance for this corpus (i.e. the best published results). Some corpora (but not all) will have public leaderboards that can help here.
4. Write code to
    1. download the corpus
    2. perform any necessary preprocessing
    3. train a machine learning method on the training set, evaluating performance on the validation set
    4. perform hyperparameter optimization
    5. evaluate your final model on the test set
5. Write a brief report summarising what you learned about the corpus, your results, and how they relate to the state of the art.

## Bonus task

As an optional bonus task, you may also do the following. Completing this bonus task in addition to the basic project gives +1 to your grade.

1. Choose 50 documents that _do not represent the text doumain of the corpus_ (e.g. online discussion vs. news)
2. Annotate these documents similarly as the original corpus has been annotated
3. Convert your annotations into a dataset
4. Evaluate your method on this additional out-of-domain test set
5. Include the results of this evaluation in your report 

## Returning your project

When returning your project, submit both your code (preferably a Python notebook with execution results included) and the report.
