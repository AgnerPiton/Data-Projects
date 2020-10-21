# My data science projects.
Click on the project to access the respective notebook.

### [Project 6: Building a Generative Adversarial Network(GAN)](https://github.com/AgnerPiton/Portfolio/blob/master/Sleep_stage_recognition.ipynb)

Overview: Building a GAN from the scratch using the MNIST dataset.

- Generator
- Discriminator
- Training
- Visualization

![](/images/MNISTgenerated.png)

### [Project 5: Sleep stage classification](https://github.com/AgnerPiton/Portfolio/blob/master/Sleep_stage_recognition.ipynb)

Overview: The task is to use Electroencephalography (EEG, brain waves) patterns to classify into sleep stages.

- Raw EEG signals were transformed into Spectrograms. A spectrogram is a visual representation of the spectrum of frequencies of a signal as it varies
with time. So a spectrogram is a 2D array, where one axis represents frequencies, and the other represents time.
- Goal of identifying which of the 5 sleep stages the participant was by using his/her brain wave signals. 
- Oversampling to balance the datasets.
- Checkpoint to extract the best model.
- Use of keras with 2 towers of 2D convolutions.
- 83% accuracy of identyfing sleep stages on validation set. 68% accuracy on unseen test set.

![](/images/Sleep_stage_training.png)

### [Project 4: Speech recognition](https://github.com/AgnerPiton/Portfolio/blob/master/Speech_recognition.ipynb)

Overview: Task is to learn to recognize which of several English words is pronounced in an audio recording. 

- Wave files transformed to arrays using Mel-frequency cepstral coefficients - Done using library python_speech_features. 
- Numpy, pandas, Keras. 
- Encoder for the words.
- Use of neural networks keras sequential model. 
- 90% accuracy of identyfing words on validation set. 88% accuracy on unseen test set.

![](/images/Speech_rec_training.png)

### [Project 3: Spatiotemporal analysis](https://github.com/AgnerPiton/Portfolio/blob/master/Spatiotemporal_analysis.ipynb)
- Explorations of a dataset of virus incidence
- Pandas, Scypy, Pysal, geopandas.
- Autocorrelation, Krigging, variogram, incidence maps and time series data.

Incidence of Virus per location:

![](/images/KNN-Autocorrelation.png)

### [Project 2: IMDB dataset explorations](https://github.com/AgnerPiton/Portfolio/blob/master/IMDB_explorations.ipynb)
- Exploration of the IMDB dataset, organizing and cleaning data.
- Pandas, NumPy, SkLearn.

Prediction of IMDB score using:
- Logistic Regression. - RMSE=1.029
- Random Forest regressor. - RMSE=0.862

![](/images/Gross.png)

### [Project 1: Housing dataset explorations](https://github.com/AgnerPiton/Portfolio/blob/master/Housing_explorations.ipynb)
- Preparing, visualizing and cleaning data.
- Pandas, Matplot, SkLearn.
- Performing Linear regression to predict median prices of houses.

Features with higher influence on housing prices. 

![](/images/Housing.png)

Biggest positive influence: Number of rooms 

Biggest negative influence: Counting of nitric-oxide 


