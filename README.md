# Endoscopic Instrument Segmentation


•	Trained a network which takes RGB endoscopic surgery frames as inputs and predicted pixel-wise segmentation mask images that labels the target surgical instrument type and background tissue. 

•	Pre-trained a simplified U-net on the endoscopic frame colorization task with MSE loss until the model converged, then loaded pre-trained weights as initialization for the segmentation task using DICE loss as network loss.

•	Introduced data augmentation (vertical and horizontal flips) and further tweaked the hyperparameters. 

•	Obtained output images of separated background and instruments with slightly passivated edges and reached 0.728 DICE score. 


<img width="850" height="290" src="https://github.com/ConnieZhu/Endoscopic-Instrument-Segmentation/blob/master/label_mask.png" />
