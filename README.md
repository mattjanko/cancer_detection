**Project synopsis.** In this project, we consider a collection of image files. Each file shows a patch of cells from a tissue biopsy, and each file has been labeled by expert diagnosticians according to whether its center region shows signs of metastatic cancer. We are interested in developing a convolutional neural network able to classify novel images of cells according to whether those cells are malignant or benign. We will train two architectures, one with a convolutional block custom-trained with the labeled image files and another with a pretrained feature extraction layer. 

Repository contests:

* cancer-detection.ipynb - a Jupyter notebook with our EDA, preprocessing, model building, hyperparameter tuning, and discussion
* submission.csv - a flat file with classifications for images in a holdout set
* PNGs with images depicting the training process, hyperparameter tuning, and classification performance on the holdout images
