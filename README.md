# TACos: Learning Temporally Structured Embeddings for Few-Shot Keyword Spotting with Dynamic Time Warping

### Kevin Wilkinghoff, Alessia Cornaggia-Urrigshardt

This repository contains the dataset KWS-DailyTalk used in our [paper](https://arxiv.org/abs/2305.10816). KWS-DailyTalk contains a selection of speech files from [DailyTalk](https://github.com/keonlee9420/DailyTalk) with manually annotated keywords for few-shot keyword spotting. The goal is to train a model using the isolated keywords provided for training and detect all keywords in the validation and test sentences.

# Dataset
The dataset is split into a train set, a validation set and a test set.
The train set has a total duration of 39 seconds and consists of 5 isolated versions for each of the following keywords: afternoon, airport, cash, credit card, deposit, dollar, evening, expensive, house, information, money, morning, night, visa and yuan.
The validation set and test set each have a duration of about 10 minutes and contain 156 and 157 sentences, respectively. Each of these sentences contains none up to several keywords such that each keyword appears about 12 times in each set. Keywords of the train set belong to different conversations than their occurances in the validation or test set.

# References
If you are using parts of this work, please cite the [original work](https://ieeexplore.ieee.org/document/10095751) on DailyTalk as well as [ours](https://arxiv.org/abs/2305.10816):

@inproceedings{lee2023dailytalk,
  author       = {Keon Lee and
                  Kyumin Park and
                  Daeyoung Kim},
  title        = {{D}aily{T}alk: {S}poken Dialogue Dataset for Conversational Text-to-Speech},
  booktitle    = {International Conference on Acoustics, Speech and Signal Processing (ICASSP)},
  publisher    = {{IEEE}},
  year         = {2023}
}

@inproceedings{wilkinghoff2024tacos,
  author = {Wilkinghoff, Kevin and Cornaggia-Urrigshardt, Alessia},
  title  = {{T}{A}{C}os: {L}earning Temporally Structured Embeddings for Few-Shot Keyword Spotting with Dynamic Time Warping},
  booktitle = {International Conference on Acoustics, Speech and Signal Processing (ICASSP)},
  year = {2024},
  publisher={IEEE},
  pages={9941--9945}
}
