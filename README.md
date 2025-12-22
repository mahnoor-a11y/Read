# Data / Text2Pose / Preprocessing / Hand Keypoints Filling

This folder contains preprocessing code for filling missing hand keypoints in JSON files.

## Files

- **average_hand_filling.py**  
  Takes a folder of JSON files as input and fills missing hand keypoints by averaging the previous and next non-zero frames.
