# ECG arrhythmia classification using a 2-D convolutional neural network.

ECG arrhythmia classification using a 2-D convolutional neural network.

The Autoencoder folder contains a basic model for anomaly detection using tensorflow for ECG signals , it is not the final model implemented.

This is an implementation of this paper: https://arxiv.org/pdf/1804.06812.pdf

The model -model.py was trained on MIT-BIH Arrythmia dataset.
This is the link to the model's weights: https://drive.google.com/file/d/17I0tyJDhTBAWF7-TEPhmSAiLEUNHmxQd/view?usp=sharing

The model can detect arrythmias of 6 types: 
1. Atrial premature contraction beat (APC)
2. Left bundle branch block beat (LBB)
3. Paced beat (PAB)
4. Premature ventricular contraction beat (PVC)
5. Right bundle branch block beat (RBB)
6. Ventricular escape beat (VEB)

The model can also predict whether an ECG is normal or not. So, there are 7 classes the model can predict.
# Using the model
You can download the model from the link mentioned above. Run main.py and mostly update requirements.xt for the required directories. You can give a csv ecg file or images of segmented ecg beats as your input. Mostly you will have a csv file of an ecg signal. 

