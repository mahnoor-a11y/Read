# Data/Text2pose/ground_truth_end2end

This folder contains code for producing ground truth frames for our end to end pipeline from testing data after frame differencing.

## Files

- **video_frames.py**
  
  * `This file takes input a testing_json folder of text2pose after data reduction`
  * `It generated the csv file containing frame names`

- **filter_ground_truth_frames.py**
   
  * `This file takes input human frames folder`
  * `Generates new folder filter data which contain only those frames which are in our testing_json folder`





