# PythonAutoKeras

As the name would suggest AutoKeras allows developers to automatically create Deep Learning models using the [Keras](https://keras.io/) API. In essence this application provides project management. All relevant details are stored on a project file which can be re-used. Should the need arise the project file can be read without human intervention.

To jumpstart your Deep Learning project several showcase examples have bene implemented using the Keras API. These examples proof the generilizations that are possible. AutoKeraswritten with Python 3 and adheres to the OOP-paradigm. Tensorflow 2used which now provides the Keras API by default.

Currently this projectin early-alpha development andnowhere near feature complete. In time a GUI using Kivy, use of Docker containers and dataset versioning will be implemented. Itpossible to transform models built using Keras to TensorFlow Lite for mobile use. Models can also be deployed for testing on REST server.

## To start AutoKeras

Command to install dependencies

$ pip3 install -r requirements.txt

Command to start the application

$ python app.py

## Showcase projects

The following showcase application are available.

1. Neural Network using Boston Housing data.
2. Convolutional Neural Network using Fashion MNIST.
3. Recurrent Neural Network using stock market data.
4. MNIST Autoencoder.
5. Advanced Convolutional Neural Network for Exoplanet detection.



Resources
https://github.com/tensorflow/docs/blob/master/site/en/tutorials/keras/save_and_load.ipynb
https://leimao.github.io/blog/Save-Load-Inference-From-TF2-Frozen-Graph/
https://medium.com/free-code-camp/build-a-handwriting-recognizer-ship-it-to-app-store-fcce24205b4b