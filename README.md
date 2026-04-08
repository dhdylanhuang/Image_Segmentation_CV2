# Image Segmentation CV2
Data Inspection and Training of Image Segmentation Model for use on CV2

Dataset can be found on Teams with the following path:
Software -> satellite_images -> Other_datasets -> labeled_ims -> archive.zip (created by Luca Löttgen)

Note: unsure who labelled this dataset, not too accurate so my theory is that a pretrained model produced the masks.

Note2: Upon unzipping archive.zip, val and test folders don't have masks. So we are only using train folder and perform K fold cross validation for metrics then we train the model on the full 803 samples in the train folder. 

After CV2 with the images collected I highly suggest someone try annotate it to get a labelled dataset or find one online.
