# dog_breed_classifier
From the dataset in kaggle, id's corresponding to the breeds that are mentioned below, have been filtered. 
['beagle','chihuahua','doberman','french_bulldog','golden_retriever','malamute','pug','saint_bernard','scottish_deerhound','tibetan_mastiff'].
After stiching the filename with the id, a python shutil utility, has been used to create the required train folder to be used by our model.
Fastai package has been used. It's an advanced package to perform deep learning tasks which is built on pytorch. 
From the reference of the documentation and the book, a cnn built using the resnet50 architecture has been employed to classify the images.
https://docs.fast.ai
The model has demonstrated an accuracy of 97.6% with three iterations. 
