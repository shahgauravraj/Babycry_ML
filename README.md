# Babycry_ML

## Abstract

Neonatal infants communicate with us through cries. The infant cry signals have distinct patterns depending on the purpose of the cries. Preprocessing, feature extraction, and feature selection from such a data needs expert attention and take much effort in audio signals. In deep learning techniques, the most important features are automatically extracted and selected. For this, it requires an enormous amount of data for effective classification. This work mainly discriminates the neonatal cries into awake, hungery, and sleepy, hug, uncomfortable. The neonatal cry auditory signals are transformed into a spectrogram image by utilizing the short-time Fourier transform (STFT) technique. The deep convolutional neural network (DCNN) technique takes the spectrogram images for input. The features are obtained from the convolutional neural network and are passed to are passed toother machine learning technique classifies neonatal cries.

## Introduction

Babies convey their needs through cries. Experienced baby care persons and parents can understand the reason for the baby's cries. Some young working parents struggled to interpret the baby's cries. The baby's cries imply their emotions, physical needs, and pathological problems from internal or external stimulation. Humans can listen to the audio signal in the frequency range from 50 to 15,000 Hz for music, 20 to 20,000 Hz for sounds, and 100 to 4,500 Hz for speech. Within this range, humans can discriminate the audio. Babies do not have control over their vocal tract so that it is more sensitive than adults. Baby cries contain information, and their crying pattern varies based on their physical and emotional state. The researchers found that there is a pattern for each kind of cry. Infant cry classification can be considered pattern recognition or speech recognition. An abnormal cry of the infant can indicate a genetic or pathological problem. Childcare experts can differentiate it. The baby cry-based recognition approach will help us know the infant's feelings from their cries. Techniques such as signal preprocessing, feature extraction, feature selection, and classification are the steps involved in baby cry classification.

## Source of the Data Set

We are making use of the dataset from the Donate-a-cry campaign. The dataset contains .wav files which will contain 3000 entries upon conversion.The dataset is opensourced on GitHub and can be obtained from the following link –
[donateacry-corpus](https://github.com/gveres/donateacry-corpus)