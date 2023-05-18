# TempAdaCos: Learning Temporally Structured Embeddings for Few-Shot Keyword Spotting with Dynamic Time Warping

### Kevin Wilkinghoff, Alessia Cornaggia-Urrigshardt

This repository contains the dataset KWS-DailyTalk used in our [paper](link to be provided). KWS-DailyTalk contains a selection of speech files from [DailyTalk](https://github.com/keonlee9420/DailyTalk) with manually annotated keywords for few-shot keyword spotting.

# Dataset
The dataset is split into a train set, a validation set and a test set.
The train set has a total duration of 39 seconds and consists of 5 isolated versions for each of the following keywords: afternoon, airport, cash, credit card, deposit, dollar, evening, expensive, house, information, money, morning, night, visa and yuan.
The validation set and test set each have a duration of about 10 minutes and contain 156 and 157 sentences, respectively. Each of these sentences contains none up to several keywords such that each keyword appears about 12 times in each set. Keywords of the train set belong to different conversations than their occurances in the validation or test set.

# References
If you are using parts of this work, please cite the [original work](https://ieeexplore.ieee.org/document/10095751) on DailyTalk as well as ours (link to be provided).
