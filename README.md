# Data / GANs / preprocessing / GAns_dataset_prepration

This folder contain code files for generating GANs training dataset.

## Contents
**Keypoints_normalization.py:** Takes a folder of JSON keypoint files as input and normalizes the keypoints.
**draw_skeleton_videos.py:** Uses the normalized keypoints to generate skeleton videos.
**frame_extraction.py:** Extracts frames from both skeleton videos and corresponding human videos.
**merge_skeleton_and_human_video_frames.py:** Combines the extracted skeleton and human frames by concatenating them side by side.

