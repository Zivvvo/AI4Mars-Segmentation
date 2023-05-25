The follow models are used for this project:

unet_3fold_trial_2000{i}_model.pth

resnet_3fold_trial_2000{i}_model.pth

i represents the fold index during 3-fold validation, it is a number from 0 to 2.
e.g. i = 0 implies that the model was trained from the first partition of K_fold_partition(X, fold = 3)

Note that unet models have prefix "unet", and FCN models have prefix "resnet". The pth files can be loaded into their respective network models via the torch.load() and model.load_state_dict() methods.

-------------------------------------------------------------------------------------------

The smaller models (trained only with 667 training images):

unet_3fold_trial_10000_model.pth

resnet_3fold_trial_10000_model.pth

The rest of the models are produced during the project for testing purposes, but were not used in the final report.


- Created by Zhe Fan, zhe.fan@mail.mcgill.ca
