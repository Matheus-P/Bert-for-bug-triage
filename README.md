# BERT-for-bug-triage

This repository contains a project i developed as an assignment in my CS degree. The students were supposed to develop a BERT model for two tasks related to Bug Triage in open source software. The training/evaluation procedure is similar to a K-Fold, but instead of evaluating the model in one section, and training on all of the words, the training dataset received a new section every iteration (the previous eval dataset), while the evaluation dataset was the next section, i.e. on the first iteration the model was trained on section 0, and evaluated on section 1, on the second it was trained on sections 0-1, and evaluated on section 2, and so on. The Jupyter notebook contains the models for two tasks, developer assignement and severity prediction, as well as the baseline models used for comparison.
