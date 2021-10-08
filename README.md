# Multi-HT100M


![Multi-HT100M](resource/dataset_vis_.jpg)

## Multilingual captions for the HowTo100M dataset

We provide the multilingual captions for the HowTo100M dataset in the following languages:
Language | code | link
-------- | ---- | ----
Englsish | en | [link](http://stoned.is.cs.cmu.edu:8765/multi_ht100m/json/how2_en.json)
German | de | [link](http://stoned.is.cs.cmu.edu:8765/multi_ht100m/json/how2_de.json)
French | fr | [link](http://stoned.is.cs.cmu.edu:8765/multi_ht100m/json/how2_fr.json)
Czech | cs | [link](http://stoned.is.cs.cmu.edu:8765/multi_ht100m/json/how2_cs.json)
Spanish | sw | [link](http://stoned.is.cs.cmu.edu:8765/multi_ht100m/json/how2_es.json)
Russian |ru | [link](http://stoned.is.cs.cmu.edu:8765/multi_ht100m/json/how2_ru.json)
Vietnamese | vi | [link](http://stoned.is.cs.cmu.edu:8765/multi_ht100m/json/how2_vi.json)
Swahili | sw | [link](http://stoned.is.cs.cmu.edu:8765/multi_ht100m/json/how2_sw.json)
Chinese | zh | [link](http://stoned.is.cs.cmu.edu:8765/multi_ht100m/json/how2_zh.json)

## Format
The how2_[lang].json file contains the captions for the HowTo100M videos. It can be read into a python dictionary where video_id as the key. Each value of the dictionary is another dictionary with the keys ['text', 'start', 'end']. The value of 'text' is a list of all the captions from the given video_id, and 'start' and 'end' are arrays correspondings to the start and end time timestamp of the captions (in second).

## HowTo100M videos
Please refer to [here](https://github.com/antoine77340/howto100m) for the list of HowTo100M videos and the video meta data 

## VTT in 9 Languages
The translated VTT in 9 languages for evaluation is available [here](https://drive.google.com/file/d/1RcFY8VHlJ6lrEqaCckn2umJeMweHFMmT/view?usp=sharing)

## Contact 
Please feel free to contact Bernie Huang (poyaoh@cs.cmu.edu or berniebear@gmail.com) if you have any questions. Thanks for your interest!
