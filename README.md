
# A Dataset for Personality Traits Detection in Bangla

Personality is one of the most complex attributes possessed by a human being that exposes the uniqueness of a person. Usually, personality traits are defined as descriptions of people in terms of relatively stable patterns of behaviors, thoughts, and emotions. Detecting and analyzing user personality plays an important role to design an effective recommendation system, Q/A system for customer care, employee assessment, and product promotions. Prior works on personality detection from user-generated text mostly conducted on the English language. However, there is no previous work and dataset available for automatic detection of user personality from Bangla text. 

Here, we presented a dataset for personality traits detection in Bangla language. To the best of our knowledge, this is the first dataset in Bangla for this problem domain and we released the dataset publicly for research purposes.


Please cite the following paper whenever you used the dataset:
```bibtex
@INPROCEEDINGS{9392722,
  author={U. {Rudra} and A. N. {Chy} and M. H. {Seddiqui}},
  booktitle={2020 23rd International Conference on Computer and Information Technology (ICCIT)}, 
  title={Personality Traits Detection in Bangla: A Benchmark Dataset with Comparative Performance Analysis of State-of-the-Art Methods}, 
  year={2020},
  pages={1-6},
  doi={10.1109/ICCIT51783.2020.9392722}
  }
```

The details statistic of the dataset is shown below:

| Category      | Total| Train | Test |
|---------------|------|-------|------|
| Aggreableness | 511  | 408   | 103  |
| Conscientiousness | 528  | 422   | 106  |
| Extroversion | 628  | 502   | 126  |
| Neuroticism | 646  | 516   | 130  |
| Openness | 687  | 549   | 138  |
| Total | 3000  | 2397   | 603  |

# Task Formulation
The major goal of the personality traits detection task is to analyze the content of the informal Bangla texts and categorize them into the most representative personality traits class. Therefore, we cast our personality traits detection as a multi-class classification problem and labels each Bangla text to the corresponding personality class. The task is formally defined as follows: 

Task: Classifying Bangla text by the user's personality traits.

Given a user-generated Bangla text, a system needs to determine the most representative personality class for this text. Standard evaluation measures including macro averages recall, precision, F1 scores, and accuracy is used to estimate the overall system performances. We consider the F1 score, macro averages across all five personality classes as the primary evaluation measure for this task.

