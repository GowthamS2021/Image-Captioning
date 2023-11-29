# Image-Captioning
Repository for CS337 course project

#Project Overview
In this project we made multiple models for Image Caption Generation.For detailed explanation please refer to the report.

#Steps to run the code
1:Install the required packages using the command "pip install -r requirements.txt".
2:Run the required model using jupyter notebook or google collab.

#Repository Structure
All the codes are in "model" folder,models made before presentation(with BLEU score) are in "pre_presentation" folder and the ones made after (with METEOR score) are in the models folder.
All the images are in "pics" folder.The codes include pre-saved outputs generated from prior runs.There are 6 codes in post presentation,each with a different encoder decoder pair.
We used 2 encoders(VGG19 ,ResNet152) and 3 decoders(LSTM,LSTMmodified,LSTM_with_attention)
