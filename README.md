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

# Hindi and English captions


|         |            |   |
| :-------------: |:-------------:| :-----:|
| ![video1470](https://github.com/alokssingh/MSR-VTT-captioning/tree/master/images/video1470.gif)| ![video618][video618] | ![video4139][video4139]|
|**Video1470**|**Video618**|**Video4139**|
|**English Captions**|**English Captions**|**English Captions**|
|hilary clinton is giving a speech to an enthusiastic crowd|a racing car passing away speedily|some people are cooking|
|a woman giving a speech|race cars driving in the wilderness|instructions on how to prepare eggs|
|hillary clinton gives a speech|cars are racing down a mountain path|a person is preparing egg whites|
|hillary clinton political video|cars are traveling down a road surrounded by people in a forest|a child is cooking in the kitchen|
|**Hindi Captions**|**Hindi Captions**|**Hindi Captions**|
|हिलेरी क्लिंटन एक उत्साही भीड़ को भाषण दे रही हैं|एक रेसिंग कार तेजी से गुजर रही है|कुछ लोग खाना बना रहे हैं|
|एक महिला भाषण दे रही हैं|जंगल में गाड़ी चलाते हुए|अंडे तैयार करने के तरीके के बारे में निर्देशं|
|हिलेरी क्लिंटन एक स्पीच दे रही हैंं|कारें एक पहाड़ी रास्ते पर दौड़ रही हैं|एक व्यक्ति अंडे की सफेदी तैयार कर रहा है|
|हिलेरी क्लिंटन राजनीतिक वीडियो|कारें एक जंगल में लोगों से घिरी सड़क पर उतर रही हैं|एक बच्चा रसोई में खाना बना रहा है|

[video1470]: https://github.com/alokssingh/MSR-VTT-captioning/tree/master/images/video1470.gif
[video618]: https://github.com/alokssingh/MSR-VTT-captioning/tree/master/images/video618.gif
[video4139]: https://github.com/alokssingh/MSR-VTT-captioning/tree/master/images/video4139.gif







Code will be uploaded soon on the acceptance of the Manuscript


# Acknowledgement:
1. [MSR-VTT: A Large Video Description Dataset for Bridging Video and Language](https://www.microsoft.com/en-us/research/wp-content/uploads/2016/06/cvpr16.msr-vtt.tmei_-1.pdf)
