# Forest Segmentation with U-Net on WorldView-2 Satellite Images

Goal: Train and evaluate best possible forest-type segmentation model with the dataset provided by the Croatian Forest Research Institute.

Challenges:
- different forest types differ in share (%) of certain species, meaning that different classes can be partly composed of the same species of tree only in different ratios. This makes classification more difficult as differences and especially boundaries between classes are subtle.
- Very small ground truth. A bigger, less-reliable synthetically generated dataset had to be used for training.

Main experiment is carried out in `work/UNet 8C Main Experiment.ipynb`

