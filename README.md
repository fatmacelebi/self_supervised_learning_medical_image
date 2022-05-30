# self_supervised_learning_medical_image

We share the codes for a Self-Supervised Learning (SSL) based method to segment and quantify the density of cellular senescence which can perform efficiently even with the limited size of dataset which is acquired from bright-field microscopy. We incorporated A Simple Framework for Contrastive Learning of Visual Representations(SimCLR) into the conventional instance segmentation algorithm, Mask R-CNN. In the SSL part, we trained ResNet-101 backbone with our unlabeled dataset by using SimCLR. Then, we used it in the downstream task with a labeled, smaller dataset consisting of unstained cell images.

We also share the pre-trained ResNet-101 models under pretrained_model folder. Here you can find and download different models which is pre-trained with different batch size or different approaches. These pretrained models can be used during transfer learning technique on medical images. All models have the same epoch which is 200 for our study. 

# Citation
