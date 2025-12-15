# Image_proccesing_Catsa_and_Dogs
 This project is about Image proccesing of cats and dogs.
 We use tansforms and optimizers to promote the code and using microsoft DATASET.
 Train model with transform and use 25 epoch for train the model.
 The Resnet18 model trained for 25 epochs using 1000 training images.
 Training was preformed over 25 complete epochs on the balanced training dataset.
 Fine-tuned the pre-trained ResNet18 for 25 epochs with a batch size 32.
 Data augmentation: Random Resize Crop, Horizatal flip, Rotation.
 Fine-tuning: Initially trained only the final fully-connected-layer,with adam optimizer.
 Transfer learning using pre-trained ResNet18 from torchvision.
#Requirements
 Python 3.8+
 Pytorch
 Torchvision
 Dataset(from Higging face)
 PIL
