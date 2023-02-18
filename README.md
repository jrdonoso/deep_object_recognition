# deep-object-recognition
Convolutional Neural Network optimised to recognise objects presented to the webcam

The model is specified, trained and evaluated in the notebook contained in /dep; details of the architecture are provided there. The training data contained in /data needs to be structured in folders (1 per object class), each of which should contain a sample of images of the respective class (folders should be named according to their respective class labels). The trained model is saved in /dep/model_object.h5 and used by the main code contained in /scr/object_recognition_loop.py, which samples frames from the webcam and recognised the object presented. 