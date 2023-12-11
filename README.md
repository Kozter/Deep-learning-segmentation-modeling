# Deep-learning-segmentation-modeling

### Medical image segmentation (experimental study)
In this project, you are required to implement deep learning models to perform the
segmentation task on the given dataset. Finally, you must write a paper based on your
results. You can follow the steps given below to complete the assignment.
The dataset: Kvasir-Instrument
The Kvasir-Instrument dataset (size 170 MB) contains 590 endoscopic tool images along
with their corresponding ground truth masks. The resolution of the images in the dataset
varies from 720x576 to 1280x1024. The image files are encoded using JPEG compression
[Ref: https://datasets.simula.no/kvasir-instrument/ ].
Data description and download link: https://datasets.simula.no/kvasir-instrument/
Use this dataset for your experiments. In this dataset, you can find train and test data splits,
which should be used as they are for your experiments. This means you have to use the
train split to train your models and the test data for evaluating your models.
### What do you need to do with the above dataset?
Train Deep Learning (DL) models for segmenting endoscopic tools from a given input image
automatically, and analyze the performance of your DL models using the following aspects:
1. Three different models (for example, UNet, UNet++, FPN, etc.).
[Sample Resources: https://github.com/qubvel/segmentation_models.pytorch ]
2. Three different data augmentation techniques with a selected model.
[Sample Resources: https://imgaug.readthedocs.io/en/latest/index.html ,
https://albumentations.ai/ ]
3. Three different activation functions with a selected model.
[Sample Resources: https://machinelearningmastery.com/activation-functions-in-pytorch/ ]
4. Three different optimization methods with a selected model.
[Sample Resources: https://pytorch.org/docs/stable/optim.html ]
5. Three different dropout rates or three different types of dropout layers.
[Sample Resources: https://pytorch.org/docs/stable/nn.html#dropout-layers ]
