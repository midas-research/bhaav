# BHAAV
A dataset of sentences from Hindi stories tagged with different emotion tags developed by

<br>
<p align="center">
  <img src="https://github.com/midas-research/bhaav/blob/master/MIDAS-logo.jpg" alt="MIDAS lab at IIIT-Delhi"  width="60%"/>
  <br>
</p>
<br>

**BHAAV** is the first and largest Hindi text corpus for analyzing emotions that a writer expresses through his/her characters in a story, as perceived by a narrator/reader. The corpus consists of 20,304 sentences collected from 230 different short stories spanning across 18 genres such as प्रेरणादायक (Inspirational) and रहस्यमयी (Mystery). Each sentence has been annotated into one of the five emotion categories **anger**, **joy**, **suspense**, **sad**, and **neutral**.



This repository contains link to download the data, and information about the corpus.

For more details on how the dataset was created, and baseline models,
please refer to our paper, [BHAAV- A Text Corpus for Emotion Analysis from Hindi Stories](https://arxiv.org/abs/1910.04073)

The dataset can be obtained from https://zenodo.org/record/3457467#.Xd07oy2ZO-t

## Dataset Overview

#### Distribution of sentences in different categories of emotions in the BHAAV dataset.

<br>
<p align="center">
  <img src="https://github.com/midas-research/bhaav/blob/master/sentence-distribution.png" alt="Sentence Distribution"  width="60%"/>
  <br>
</p>
<br>

#### Inter-annotator agreements for each genre and for the entire dataset as measured using Fleiss‘s Kappa.

<br>
<p align="center">
  <img src="https://github.com/midas-research/bhaav/blob/master/inter-annotator-agreements.png" alt="Interannotator Agreement"  width="60%"/>
  <br>
</p>
<br>

#### Sample sentences from BHAAV dataset for each emotion label.

<br>
<p align="center">
  <img src="https://github.com/midas-research/bhaav/blob/master/sample-sentences.png" alt="Sample Sentences"  width="90%"/>
  <br>
</p>
<br>

#### Performance of the baseline supervised classification models on BHAAV dataset.

<br>
<p align="center">
  <img src="https://github.com/midas-research/bhaav/blob/master/baseline-performance.png" alt="Baseline Performance"  width="60%"/>
  <br>
</p>
<br>

#### Top 10 most important features for each emotion category as identified by the Logistic Regression model during training.

<br>
<p align="center">
  <img src="https://github.com/midas-research/bhaav/blob/master/important-features.png" alt="Important Features"  width="60%"/>
  <br>
</p>
<br>

#### Flow of emotions in randomly selected stories from two different genres.

<br>
<p align="center">
  <img src="https://github.com/midas-research/bhaav/blob/master/emotion-flows.png" alt="Emotion Flows"  width="90%"/>
  <br>
</p>
<br>

## Terms of Use

1. This corpus can be used freely for research purposes.
2. The paper listed below provide details of the creation and use of the corpus. If you use the corpus, then please cite the     paper.
3. If interested in commercial use of the corpus, send email to midas@iiitd.ac.in.
4. If you use the corpus in a product or application, then please credit the authors and [Multimodal Digital Media Analysis Lab - Indraprastha Institute of Information Technology, New Delhi](http://midas.iiitd.edu.in) appropriately. Also, if you send us an email, we will be thrilled to know about how you have used the corpus.
5. Multimodal Digital Media Analysis Lab - Indraprastha Institute of Information Technology, New Delhi, India disclaims any responsibility for the use of the corpus and does not provide technical support. However, the contact listed above will be happy to respond to queries and clarifications.
6. Rather than redistributing the corpus, please direct interested parties to this [page](https://github.com/midas-research/bhaav)

Please feel free to send us an email:
- with feedback regarding the corpus.
- with information on how you have used the corpus.
- if interested in having us analyze your data for emotion, and other affectual information.
- if interested in a collaborative research project.

Copyright (C) 2019 Multimodal Digital Media Analysis Lab - Indraprastha Institute of Information Technology, New Delhi (MIDAS, IIIT-Delhi)

## References

Please cite [[1]](https://arxiv.org/abs/1910.04073) if you found the resources in this repository useful.


[1] Kumar, Y., Mahata, D., Aggarwal, S., Chugh, A., Maheshwari, R., and Shah, R. R. [*BHAAV- A Text Corpus for Emotion Analysis from Hindi Stories*](https://arxiv.org/abs/1910.04073)


```
@article{kumar2019bhaav,
  title={BHAAV-A Text Corpus for Emotion Analysis from Hindi Stories},
  author={Kumar, Yaman and Mahata, Debanjan and Aggarwal, Sagar and Chugh, Anmol and Maheshwari, Rajat and Shah, Rajiv Ratn},
  journal={arXiv preprint arXiv:1910.04073},
  year={2019}
}
```

