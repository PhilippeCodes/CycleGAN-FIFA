# FIFA-CycleGAN
🎮 Turn FIFA 20 Gameplay into real-life Football using a CycleGAN

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1qhN8qg6yg-AOhaQtYap-iRugc6mCSxUz#scrollTo=KKpTn90t6oCy)

In this project, we attempt to transform frames of FIFA 20 gameplay into real-life football broadcasts.
In order to do so, we implement a CycleGAN in Keras.
We train the CycleGAN on 1000 pictures of FIFA Gameplay and a Champions League Broadcast of Barcelona vs. Liverpool.

The CycleGAN is implemented according to the specifications of the original paper.
We train the models for 100 epochs. After every epoch, we save all the models to google drive and further plot the current results of the A-to-B transformation as well as save a plot of the Losses.

The Models and Training Data can be downloaded here:  
[Training Data (.npz)](https://drive.google.com/open?id=1sjmBlMgqrNDL4HCySr-x_FpNNa-ciSnk)  
[Models (.h5)](https://drive.google.com/open?id=12w_ivWNkdAtFqllG9qeOvTbE8BPCfdqU)  

Finally, we play around with a SRGAN and achieve impressive results in upscaling pictures of real-life soccer however, this method fails to improve our CycleGAN Result.

Feel free to play around and adapt this code to your problem.  
Don't hesitate to ask me if you have any questions!


