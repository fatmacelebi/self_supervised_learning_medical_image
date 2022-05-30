# self_supervised_learning_medical_image

We share the codes for a Self-Supervised Learning (SSL) based method to segment and quantify the density of cellular senescence which can perform efficiently even with the limited size of dataset which is acquired from bright-field microscopy. We incorporated A Simple Framework for Contrastive Learning of Visual Representations(SimCLR) into the conventional instance segmentation algorithm, Mask R-CNN. In the SSL part, we trained ResNet-101 backbone with our unlabeled dataset by using SimCLR. Then, we used it in the downstream task with a labeled, smaller dataset consisting of unstained cell images.
![image](https://user-images.githubusercontent.com/97739552/170995679-4385caaf-95be-40e2-940b-c9ee3ef7a9f7.png)


We also share the pre-trained ResNet-101 models under pretrained_model folder. Here you can find and download different models which is pre-trained with different batch size or different approaches. These pretrained models can be used during transfer learning technique on medical images. All models have the same epoch which is 200 for our study. 

# Citation
Please use below to cite this paper if you find this repository useful or if you use pretrained models shared here in your research.









# Results 
