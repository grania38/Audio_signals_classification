This project is about audio signals classification.<br>

- I chose the ESC-50 dataset which is a labeled collection of 2000environmental audio recordings suitable for the sounds classification. 
It consists of 5 second long recordings organized into 50 classes with 40 examples per class loosely arranged into 5 major categories: 
animals, natural soundscapes and water sounds, human and non-speech sounds, interior/domestic sounds and exterior and urban noises.<br>
![alt text](https://github.com/grania38/Audio_signals_classification/blob/main/image1.jpg?raw=true)


- Convolutional neural networks. The cnn I used designed in the figure is designed to learn and exrtract relevant patterns from audio signal which can be used to make good predictions. So the signal goes through a series of convolutional layers that discern local features of the audio and reduces the size of the data to enhance computationally efficiency. After that the output goes under a succession of activation functions that understand more complex relations in the audio. After that the output goes througha series of pooling layers they are responsible for reducing overfitting and the spatial dimensions of the input volume.
Then we have the fully connected layer, responsible for making the final predictions.
![alt text](https://github.com/grania38/Audio_signals_classification/blob/main/image2.jpg?raw=true)

- Software tools used: Google colab, python, librosa, scikit learn, Keras and Pytorch.
  ![alt text](https://github.com/grania38/Audio_signals_classification/blob/main/image3.jpg?raw=true)
  ![alt text](https://github.com/grania38/Audio_signals_classification/blob/main/image4.jpg?raw=true)
  ![alt text](https://github.com/grania38/Audio_signals_classification/blob/main/image5.jpg?raw=true)
  ![alt text](https://github.com/grania38/Audio_signals_classification/blob/main/image6.jpg?raw=true)
  ![alt text](https://github.com/grania38/Audio_signals_classification/blob/main/image7.jpg?raw=true)
  ![alt text](https://github.com/grania38/Audio_signals_classification/blob/main/image8.jpg?raw=true)
