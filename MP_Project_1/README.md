# MP_Project1
Visual Transformer and CNN architectures with adversarial attack examples using Pytorch for CIFAR-10 Dataset

## Contents
### CNN notebook 
The CNN noteboook **Machine_Perception_Project_1.ipynb**, includes all code required to train and evaluate a convolutional neural network on the CIFAR-10 dataset. It contains the complete model architecture, training loop, and testing procedures, along with visualizations of performance metrics.

### Transformer Folder

**transformer.ipynb:** Notebook containing all of the ViT code including the from scratch model and the pre-trained model.

**res:** Saved results of the trianing loss, testing accuracy and model weights for the seed used in the transformer notebook.


### Adversarial Attacks Folder
**PGD.ipynb**: Notebook that contains adversarial attack code on the ViT architecture using FGSM and PGD attack. The results in the report are taken from this notebook. 

**PGD_seeded.ipynb**: Notebook that contains the same code. However, the other version is not seeded so the results are not reproducible. This version is seeded for reproducible results. The performance between each seeds are very similar. 


