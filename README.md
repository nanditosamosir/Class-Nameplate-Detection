# **Class Nameplate Detection**

It is a class signboard detection project. The dataset consists of images that have been given a bounding box for the location of the class signboard with the label "papan_nama". There is only 1 class, because the focus of this project is to detect the location of the class signboard, then the location is marked with a bounding box. 

- The model uses InceptionV3 with a training process of 25 epochs.
  
- To run this code, please download `model_InceptionV3.ipynb` file first, then upload it to google colab.

Class detection accuracy shows 100% accuracy results on train and validation.

![model_accuracy](https://github.com/user-attachments/assets/c3637f74-0a43-4cbf-a98a-7bb64c0a3314)


The loss model can be seen in the following graph.

![model_loss](https://github.com/user-attachments/assets/fab4a985-4b1c-48ae-847c-b8a1ad192454)

The bounding box reg_mae

![model_bbox_reg_mae](https://github.com/user-attachments/assets/270a3549-834a-4ead-83f2-115d6db3d490)

Some examples of the results of making bounding boxes.

![output_1](https://github.com/user-attachments/assets/058235c4-2ad7-4bb6-b77c-10372b4ef5c3)

- The trained model is converted with the .keras extension.
