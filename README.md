# Retinopathy
Retinopathy Classification using Tensorflow

run_prediction.py uses trained model parameters and graph in retinopathy_serve/
to classify the retina images dr4.tiff and healthy.tiff according to their degree of pathology: 0 to 4. For each image, the output is a probability distribution among the five classes.

Later on there will be another python file and training data that will perform the training of the Tensorflow model used in run_prediction.py.
