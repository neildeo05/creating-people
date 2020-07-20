# GAN that creates faces using the LFW dataset


## Download/Running
  
- Clone this project
- Navigate to https://www.kaggle.com/jessicali9530/lfw-dataset, and hit download. Make sure the destination is the path of this project.
- Extract the contents of the .zip file
- The file you want to run is "faces.ipynb"


## Notes

Built using PyTorch. Both the discriminator and the generator are feedforward neural networks.

I don't have an NVIDIA GPU, so I had to use google colab gpu hardware accelerator.

If you don't want to train the model on a GPU, then remove all the  ".to(torch.device("cuda"))" from the faces.ipynb file.



## Credit

The LFW (labelled faces in the wild) dataset is created by UMASS CS, http://vis-www.cs.umass.edu/lfw/

I downloaded the dataset from kaggle, at the link mentioned above



