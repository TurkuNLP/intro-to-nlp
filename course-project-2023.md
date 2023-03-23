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

| Corpus name | Labels | Subset sizes  | Description |
| ------------- | ------ | ------------- | ----------- |
| [imdb](https://huggingface.co/datasets/imdb) | neg pos | train:25000 unsupervised:50000 test:25000 | Large Movie Review Dataset. This is a dataset for binary sentiment classification containing substantially more data than previous benchmark datasets. We provide a set of 25,000 highly polar movie reviews for training, and 25,000 for testing. There is additional unlabeled data for use as well. |
| [amazon_polarity](https://huggingface.co/datasets/amazon_polarity) | negative positive | train:3600000 test:400000 | The Amazon reviews dataset consists of reviews from amazon. The data span a period of 18 years, including ~35 million reviews up to March 2013. Reviews include product and user information, ratings, and a plaintext review.  |
| [rotten_tomatoes](https://huggingface.co/datasets/rotten_tomatoes) | neg pos | train:8530 validation:1066 test:1066 | Movie Review Dataset. This is a dataset of containing 5,331 positive and 5,331 negative processed sentences from Rotten Tomatoes movie reviews. This data was first used in Bo Pang and Lillian Lee, ``Seeing stars: Exploiting class relationships for sentiment categorization with respect to rating scales.'', Proceedings of the ACL, 2005.  |
| [sst2](https://huggingface.co/datasets/sst2) | negative positive | train:67349 validation:872 test:1821 | The Stanford Sentiment Treebank consists of sentences from movie reviews and human annotations of their sentiment. The task is to predict the sentiment of a given sentence. We use the two-way (positive/negative) class split, and use only sentence-level labels.  |
| [emo](https://huggingface.co/datasets/emo) | angry happy others sad | train:30160 test:5509 | In this dataset, given a textual dialogue i.e. an utterance along with two previous turns of context, the goal was to infer the underlying emotion of the utterance by choosing from four emotion classes - Happy, Sad, Angry and Others.  |
| [emotion](https://huggingface.co/datasets/emotion) | anger fear joy love sadness surprise | train:16000 validation:2000 test:2000 | Emotion is a dataset of English Twitter messages with six basic emotions: anger, fear, joy, love, sadness, and surprise. For more detailed information please refer to the paper.  |

**Note**: if you choose a corpus that does not have a validation set, you should split off a random portion of the training data to use for validation.

## Bonus task

As an optional bonus task, you may also do the following. Completing this bonus task in addition to the basic project gives +1 to your grade.

1. Choose 50 documents (or 100 documents if group project) that _do not represent the text domain of the corpus_ (e.g. online discussion vs. news)
2. Annotate these documents similarly as the original corpus has been annotated
3. Convert your annotations into a dataset
4. Evaluate your method on this additional out-of-domain test set
5. Include your annotated data and the results of this evaluation in your report 

## Returning your project

Return your project as a Python notebook that includes both execution results and the summary descriptions detailed above.
