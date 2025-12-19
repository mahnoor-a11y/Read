# Data/GANs/data_reduction

This folder contains the code used for cropping the frames.
## Files

- **keep_15_frames.py**
  
  * `Takes all video JSON keypoints as input and generates a CSV file indicating whether each frame should be kept or skipped.`
  * `The script also creates separate keep and skip folders and moves the corresponding frames into these folders based on their status`

- **move_frames.py**
   
   This file takes input the above generated csv and move the frames with status of keeep to one folder with naming convention poseid_word_instance_frame_name.png





