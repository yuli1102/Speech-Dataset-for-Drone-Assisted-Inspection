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

1. Upload the audio data in image format. Three format images are provided in "Releases": Mel-spectrogram, Spectrogram, and MFCC. Mel-spectrogram data is used in model development in this paper.  The code for achieving these format image can be found in "Comparison-Experiment-Code\Input and Feature\Local Data comparison\get_images-audio.ipynb".
These data are used for model development comparison, therefore only subject 1-5 data are included. The follwing examples are converted from an utterance of the keyword “continue” spoken by subject #5.

Mel-Spectrogram            |  MFCC          | Spectrogram
:-------------------------:|:-------------------------:|:-------------------------:
![Mel-Spectrogram](https://user-images.githubusercontent.com/44143351/196063055-22daed5f-e310-47f2-af3d-e03c76381e96.png)|  ![MFCC](https://user-images.githubusercontent.com/44143351/196063056-85ddc17e-1130-42cf-8062-9a1a2b97c2f2.png)|  ![Spectrogram](https://user-images.githubusercontent.com/44143351/196063057-49f528d4-ed56-479d-b76a-a17cacf9c32d.png)



2. Upload the model code. (to be added)

3. (1) Upload the code of comparing the model using different inputs (Mel-spectrogram, Spectrogram, and MFCC) and different feature extractors (VGG, ResNet50, and INCEPTION_Resnet_v2" in the folder of "Comparison-Experiment-Code\Input and Feature". (2) Upload the code of comparing the speaker verification methods of our Ratio method with the d-vector End to end method in the folder of "Comparison-Experiment-Code\Speaker Verification". Note: Local data stands for the data in Releases, and the Digit data is downloaded from [AudioMNIST](https://github.com/soerenab/AudioMNIST). 




# Initial update in June 2022
A Speaker-Keyword Recognition Multi-tasking Model for Keeping Human in the Loop of Drone Assisted Inspection

Data can be downloaded from "Releases". These Mel-spectrogram images are converted from 1.5 seconds audio segments splitted from our raw audio data.  
These data are collected from 8 subjects with 10 different keywords of "BIRDS, Task, One, Two, Three, Four, Backward, Continue, Hover, Stop”.
In the paper, 5 subjects are used to develop an initial model, and data from subject 6-8 are used for model adaption. 
