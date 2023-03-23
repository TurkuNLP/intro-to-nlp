# Course project

To complete the course, successful completion of the project described here is required. The project affects grading as follows:

* Exam gives **grades up to 4** with a minimally completed project (required to pass the course)
* Project completed with bonus task (see below) gives **+1 to grade**
* A very well completed project (carried out meticulously and with attention to detail) gives **+1 to grade**

For example, if you get a 3 on the exam but complete the bonus task (+1) _and_ complete your project very well (+1), your grade will be 5.

## Group work

The project can be completed either individually or as a group of two people. Group projects have some additional requirements; see below.

## Basic project outline

The project involves creating a machine learning-based method for a text classification task of your choice. Specifically, you should

1. Select a text classification corpus to work on. (see below)
2. Read the paper presenting the corpus as well as any other relevant published materials about the corpus to assure you understand the data
3. Identify what is the state-of-the-art performance for this corpus (i.e. the best published results). Some corpora (but not all) will have public leaderboards that can help here.
4. Write code to
    1. download the corpus
    2. perform any necessary preprocessing
    3. train a machine learning method on the training set, evaluating performance on the validation set
    4. perform hyperparameter optimization
    5. evaluate your final model on the test set
5. Write a summary of
    1. what you learned about the corpus
    2. your results
    3. how your results relate to the state of the art
    4. if completed as a group project, a section detailing who did what

### Text classification corpora

Choose one of the following corpora to work on. (If you'd prefer to suggest a corpus not listed here, get in touch with us on Discord!)

1. TODO
2. TODO
3. TODO

## Bonus task

As an optional bonus task, you may also do the following. Completing this bonus task in addition to the basic project gives +1 to your grade.

1. Choose 50 documents (or 100 documents if group project) that _do not represent the text domain of the corpus_ (e.g. online discussion vs. news)
2. Annotate these documents similarly as the original corpus has been annotated
3. Convert your annotations into a dataset
4. Evaluate your method on this additional out-of-domain test set
5. Include your annotated data and the results of this evaluation in your report 

## Returning your project

Return your project as a Python notebook that includes both execution results and the summary descriptions detailed above.
