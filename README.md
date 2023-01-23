# MS-segmentation-model
Multiple sclerosis is a disease of the central nervous system that is characterized by inflammation and neuroaxonal degeneration in both gray matter and white matter. Only three subtypes of multiple sclerosis out of seven can be identified using MR images. Moreover, multiple sclerosis frequently involves lesions that may be appear on a scan at one time-point, but not in the subsequent time points. 
The disease can be hard to identify due to the randomity it occurs, the sizes of the white matter lesions and the locations it evolves.
The project segmentate MS lesions using model based on a Unet architecture that contains encoder and decoder layers which combine together to extract more feature information.
After conducting research on various hyperparameters and different modalities we came to the conclusion that T-2 Modality together with “Binary Focal Cross entropy” with a Gamma=3 loss function, Adam optimizer, Unet with the depth of 4, learning rate = 1e^(-5),  gave us most accurate results.
This project demonstrated the importance of hyperparameters and their effect on the learning process of the model, and how small change makes a big difference.
 
