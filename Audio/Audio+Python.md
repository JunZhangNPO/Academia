*Basic packages 
pandas
matplotlib.pyplot
numpy 
seaborn
tensorflow


* Audio relevant Packages
Librosa  //ffmpeg--add it into environmental variable
pyaudio  //cross platform audio output/input stream library
wave //

* librosa.load // 
offset & duration: get a part of the audio 
The unit of duration is second.
sr: sampling rate // The unit is hz. 
soundlife: save the document 

* librosa.display
librosa.display.waveshow //waveform
librosa.display.waveplot 
librosa.display.specshow //Mel power spectogram


 *indicators 
 librosa.feature.mfcc  // MFCC; three DCT types, the default is 2; Mel Frequency Cepstral Coefficient
 librosa.feature.delta // difference， order 1/2
 import dtw // DTW(Dynamic Time Warping), to compare the similarities of two sounds // distance, cost, accuracy, path 
 
**Figures 
librosa.filters.mel
htk
Fbank


**pre-processing 
delete silence: librosa.effects.trim
transform waveform into numbers 
decoder
neural network 

**Speech Emotion Analyzer
Feature Extraction--Pitch/MFCC--Model Training-Trained Classifier
several seconds/two sentences

package: keras // for deep learning 
scipy
sklearn

label: positive, negative, neutral 
data splitting 
data augmentation

model.summary()
Epoch
Train valid loss graph 
test data 
confusion matrix 

** speech to text 
CNN
longitudinal wave
package: Ipython.display as ipd
sample rate 

one-hot-coding // convert the integer encoded labels to a one-hot vector
Con1vd: one dimension CNN
model.compile 
call back, early stopping 
random 
