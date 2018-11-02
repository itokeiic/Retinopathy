# Retinopathy
Retinopathy Classification using Tensorflow

This repository is a partial copy of the following repository of Niklas Köhler for use in the DEEP-Hybrid-DataCloud project:
https://gitlab.com/niklaskoehler/retinopathy_model

run_prediction.py uses trained model parameters and graph in retinopathy_serve/
to classify the retina images dr4.tiff and healthy.tiff according to their degree of pathology: 0 to 4. For each image, the output is a probability distribution among the five classes.
In the same directory as run_prediction.py run the following in the console.

python3 run_prediction.py --model_dir './retinopathy_serve/' --image_file dr4.tiff,healthy.tiff

resnet_model.py and resnet_run_loop.py are are two files from Tensorflow that are used in defining and training the ResNet model.  At this point, we don't need these files.

Later on, there will be another python file and training data that will perform the training of the Tensorflow model used in run_prediction.py.
