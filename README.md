## Citation
If you use this repository, please cite the following paper:

Li, Y., Parsan, A., Wang, B., Dong, P., Yao, S., & Qin, R. (2022). A Multi-tasking Model of Speaker-Keyword Classification for Keeping Human in the Loop of Drone-assisted Inspection. arXiv preprint arXiv:2207.04027.

~~~~  
@article{li2022multi,
  title={A Multi-tasking Model of Speaker-Keyword Classification for Keeping Human in the Loop of Drone-assisted Inspection},
  author={Li, Yu and Parsan, Anisha and Wang, Bill and Dong, Penghao and Yao, Shanshan and Qin, Ruwen},
  journal={arXiv preprint arXiv:2207.04027},
  year={2022}
}
~~~~

# Update in Oct 2022:

1. Upload the audio data in image format. Three format images are provided in "Releases": Mel-spectrogram, Spectrogram, and MFCC. Mel-spectrogram data is used in model development in this paper.  The code of achiving these format image can be found in "Comparision-Experiment-Code\get_images-audio.ipynb".
These data is used for model development comparision, therefore only subject 1-5 data are inlcuded. 

2. Upload the model code. (to be added)

3. Upload the code of comparing the model using different input (Mel-spectrogram, Spectrogram, and MFCC) and different feature extracor (VGG, ResNet50, and INCEPTION_Resnet_v2" in the folder of "Comparision-Experiment-Code".

# Initial update in June 2022

# Speech-Dataset-for-Drone-Assisted-Inspection
A Speaker-Keyword Classification Multi-tasking Model for Keeping Human in the Loop of Drone Assisted Inspection

Data can be downloaded from "Releases". These Mel-spectrogram images are converted from 1.5 seconds audio segments splitted from our raw audio data.  
These data are collected from 8 subjects with 10 different keywords of "BIRDS, Task, One, Two, Three, Four, Backward, Continue, Hover, Stop”.
In the paper, 5 subjects are used to deveop an initial model, and data from subject 6-8 are used for model adaption. 
