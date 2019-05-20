# ID2223
Repository for the ID2223 Scalable Machine Learning and Deep Learning course at KTH.

## Description of the project 

The most powerful politician in the world is the American president. That person should have the ability to speak in a proper way to affect the people. To hold a speech is one of the most important tools of politicians to communicate with the public.

Donald Trump is the current president of the USA. He is known for his iconic and very "specific" speeches.
But are they also unique? Is a neural network able to reproduce a speech that sounds like a common Donald Trump speech?

This project tries to produce an artificial speech which sounds like Mr Trump. The dataset which is used is a collection of 834 speeches from 2016-2017. A special recurrent neural network called "Long Short Term Memory" (LSTM) is built using Keras. In the end, the network shall be used to see if a politician like Trump can be replaced by a machine.

## Report

The results and the explanation of this project are available in the report.

## How to run it

1. Download this repository.
2. Install Tensorflow and Keras. Since some people have issues while installing these two packages, be sure to follow these instructions in this order : 

```pip install --upgrade tensorflow
pip install numpy scipy
pip install scikit-learn
pip install pillow
pip install h5py
pip install keras
```

For the other packages, just use ```pip install name_package``` where name_package is the name of the package.

Note : If you can not manage to install correctly Tensorflow and Keras, you can directly use google colab at : https://colab.research.google.com/

3. Download the weights of the LSTM network and load them in your .ipynb file.
4. Generate the speeches !




