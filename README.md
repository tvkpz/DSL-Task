DSL Task Repository
====

This is the official repository for the Disciminating between Similar Language (DSL) Shared Task 2015. The results of the DSL-2015 Shared Task can be found on https://goo.gl/dCaxAV 

This repo contains the following:
 - DSL Corpus Collection (DSLCC) version 2.0 (training, dev, test and gold data included)
 - DSL Shared Task submissions from participating teams
 - The script to blind Named Entities (NEs) for the Test Set B in DSL-2015
 - The evaluation script to evaluate your outputs (`evaluate.py`)
 - The evaluation script to evaluate all submitted systems (`evaluate_submissions.py`)

To Evalute Your Output
====

Here's an example to evaluate your system output:

```
$ git clone https://github.com/Simdiva/DSL-Task.git
$ cd DSL-Task
$ python3 evaluate.py submissions/mms/mms-tfidf-close-run1.txt data/DSLCC-v2.0/gold/test-gold.txt
```






