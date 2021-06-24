# MSR-VTT-Hindi-video-captionig
The MSR−VTT dataset started by Microsoft research community consist of 10K videos. The dataset is collected
based on 257 queries with average 118 videos for each queries. The separation of dataset for training and validation
is done as per the statistics given in [[1]](https://www.microsoft.com/en-us/research/wp-content/uploads/2016/06/cvpr16.msr-vtt.tmei_-1.pdf).  This repository contains the MSR-VTT video captioning dataset in Hindi. To maintain the integrity of MSR−VTT dataset, all the 20 English captions of each video are translated to Hindi. The output Hindi captions of Google translator need to be post-edited due to the presence of some erroneous translated Hindi captions. These errors are mostly due to ambiguous word sense and typo.

NOTE: Details of video with their ids are available [here](http://ms-multimedia-challenge.com/2017/dataset)

 **Dataset detail**:
| Data seperation  | # Videos  | # Hindi caption | # English caption |
| ------------- | ------------- |------------- |------------- |
| Training  | 6153  | 123060  |123060  |
| Validation  | 497  | 9940  |9940  |
| Test  | 2990  | 59800  |59800  |

**Sample Hindi and English captions**


|**Video1470**|**Video618**|**Video4139**|
 :-------------: |:-------------:| :-----:|
|<img src="https://github.com/alokssingh/MSR-VTT-captioning/blob/master/images/video1470.gif" width="250" height="250"/> |<img src="https://github.com/alokssingh/MSR-VTT-captioning/blob/master/images/video618.gif" width="250" height="250"/> |<img src="https://github.com/alokssingh/MSR-VTT-captioning/blob/master/images/video4139.gif" width="360" height="250"/>|
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


**Dataset**

To get whole data with video please fill the [google form](https://docs.google.com/forms/d/e/1FAIpQLScG2CgspdzbbEsBLDhDLXunUJkggqAvl5fHgDqVj6HwTSSOPg/viewform?usp=sf_link), we will mail you all the details.




**Acknowledgements:**
1. [MSR-VTT: A Large Video Description Dataset for Bridging Video and Language](https://www.microsoft.com/en-us/research/wp-content/uploads/2016/06/cvpr16.msr-vtt.tmei_-1.pdf)
2. [A Comprehensive Review on Recent Methods and Challenges of Video Description](https://arxiv.org/abs/2011.14752)
3. [NITS-VC System for VATEX Video Captioning Challenge 2020](https://arxiv.org/abs/2006.04058)
4. [Attention based video captioning framework for Hindi](https://link.springer.com/article/10.1007/s00530-021-00816-3)
