# Data/GANs/data_reduction

This folder contains code for reducing redundant frames, ensuring that a maximum of 15 instances are retained.

## Files

- **keep_15_frames.py**
  
  * `Takes all video JSON keypoints as input and generates a CSV file indicating whether each frame should be kept or skipped.`
  * `The script also creates separate keep and skip folders and moves the corresponding frames into these folders based on their status`

- **move_frames.py**
   
  Uses the generated CSV file to move frames marked as keep into a single folder. The frames are renamed using the following convention:
  poseid_word_instance_frame_name.png





