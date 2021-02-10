# MSR-VTT-Hindi-video-captionig
The MSR−VTT dataset started by Microsoft research community consist of 10K videos. The dataset is collected
based on 257 queries with average 118 videos for each queries. The separation of dataset for training and validation
is done as per the statistics given in [1](https://www.microsoft.com/en-us/research/wp-content/uploads/2016/06/cvpr16.msr-vtt.tmei_-1.pdf). To maintain the integrity of MSR−VTT dataset, all the 20 English captions of each video are translated to Hindi. The output Hindi captions of Google translator need to be post-edited due to the presence of some erroneous translated Hindi captions. These errors are mostly due to ambiguous word sense and typo. This repository contains the MSR-VTT video captioning dataset in with translated Hindi captions used in the paper [Attention Based Video Captioning Framework for Hindi]()


# Dataset detail:
| Data seperation  | # Videos  | # Hindi caption | # English caption |
| ------------- | ------------- |------------- |------------- |
| Training  | 6153  | 123060  |123060  |
| Validation  | 497  | 9940  |9940  |
| Test  | 2990  | 59800  |59800  |


Code will be uploaded soon on the acceptance of the Manuscript


# Acknowledgement:
1. [MSR-VTT: A Large Video Description Dataset for Bridging Video and Language](https://www.microsoft.com/en-us/research/wp-content/uploads/2016/06/cvpr16.msr-vtt.tmei_-1.pdf)
