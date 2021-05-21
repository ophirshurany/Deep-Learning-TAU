Files and Structure:
The shared folder contains 4 different notebooks:
1. “Q3_VAE_Train.ipynb” used to train VAE (encoder + decoder) and the SVMs for the question 3.
2. “Q3_VAE_Test.ipynb” used to load pre-trained weights for the Decoder and the SVMs; to test
the images generation and the accuracy of SVMs on the test set.
3. “Q4_GAN_Train.ipynb” used to train the WGAN and DCGAN architectures for the question 4.
4. “Q4_GAN_Test.ipynb” used to load pre-trained GANs and to test images generation with these
models.
Training Notebooks:
The relevant notebooks can be run from scratch to train the VAE/GAN models. In addition, the
notebooks create and save Models and their weights for later usage.
Model Testing:
The relevant notebooks can be run independently, using the pre-saved weights. The data was created
from the Training Notebooks and saved on publicly shared Dropbox.
Important Note:
The testing notebooks load pre-trained weights and models definitions from publicly shared Dropbox
folder. This was done for more convenient development process: using multiple accounts to train on
multiple notebooks and to eliminate the need of manual confirmation of GDrive.
If for some reason the process on downloading, unzipping or inflating the files is not convenient – the
same files are saved in the files shared folder