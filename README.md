# FIFA-CycleGAN
🎮 Turn FIFA 20 Gameplay into real life Football using a CycleGAN

In this project I attempt to transform frames of FIFA 20 gameplay into real life football broadcasts.
In order to do so we implement a CycleGAN in Keras.
We train the CycleGAN on 1000 pictures of FIFA Gameplay and a Champions Leaue Broadcast of Barcelona vs. Liverpool.


The CycleGAN is implemented according to the specifications of the original paper.
We train the models for 100 epochs. After every epoch, we save all the models to a google drive and further plot the curreent results of the A-to-B transformation as well as save a plot of the Losses.

The Models and Training Data can be downloaded here:
Training Data (.npz)
![Training Data (.npz)](https://drive.google.com/open?id=1sjmBlMgqrNDL4HCySr-x_FpNNa-ciSnk)


Feel free to play around and adapt you this code to your problem.  
Don't hesitate to ask me if you have any questions!


