
# Underwater Detection

This is a YOLOv3-based model that detects cracks and rust/mess

## Setup Instructions
1.Clone repo with submodules:git clone --recurse-submodules  https://github.com/srinidhi1-dwarak/basic-underwater_detection.git

2. Set up a Python virtual environment:
3. Run script;customtrain.py
## File Structure

- `dataset/`: Contains train, valid, and test datasets.train further contains images(which has images and labels) and labels which have only the labels.
- `darknet/`: Contains YOLOv3 implementation and configuration files.
- `backup/`: Stores trained weights.

note:while running the custom script ensure images and labels are in the same folder.
