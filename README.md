# Automatic Speech Recognition

ASR model is implemented with the help of machine leaning and natural language processing.<br/>
• Dataset used for this task is sourced from Google.
The dataset is composed of  short (one-second or less) audio clips of commands, such as "down", "go", "left", "no", "right", "stop", "up" and "yes".
Each of 8 commands have 1000 different samples of voices.
Each  WAV file contains time-series data with a set number of samples per second.
Each Sample represents the amplitude of the audio signal at that specific time.
The total  dataset consists of 8k samples which is  further splitted  in 80% training samples and 10%-10% for validating and testing 
.<br/>
• Implemented CNN model on the frequency graphs of these
speeches.<br/>
• analysed the result with the help of F1 score.<br/>

### Methodology Used

We have used a CNN( convolutional neural network) model,  CNN utilizes correlations which exist with the input data. Each concurrent layer of the neural network connects some input neurons.<br />
First of all  our  data is  in .wav form.<br />
We will transform these  waveforms from the time-domain signals into the frequency-domain signals by computing the short-time Fourier transform (STFT) to convert the waveforms to as spectrograms, which show frequency changes over time.<br />
Spectrogram is a visual way of representing the signal strength or loudness of a signal over time at various frequencies.
These can be represented as 2D images<br />
To feed data in our model we have used these spectrogram images .<br />

