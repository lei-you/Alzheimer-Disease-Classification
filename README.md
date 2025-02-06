# Alzheimer-Disease-Classification

## Objective
In this project, we are trying to predict the current AD stages of the patients with multi-modality data.
## Details
In the following figure, we utilize contrastive learning-based model[1] to set up the prediction model.
Different from the original model, we employ the image features from 3D T1 MR brain images, the genetic features and the stage information from ADNI[2].
For image feature extraction, a pre-trained 3DCNN is utilzied to extract 256-d embeddings. For genetic feature extraction, a multi layer perception model is trained to get the 128-d gentic features.
Compared with single modality-based models(image, genetic), our proposed method has increased the AD staging prediction accuracy from 65% to 82% on the ADNI test data.
![AD](https://github.com/user-attachments/assets/ab732182-e2f6-4d24-9abc-0c43c300e07d)


[1]https://arxiv.org/abs/2103.00020
[2]https://adni.loni.usc.edu/
