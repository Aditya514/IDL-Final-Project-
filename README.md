# IDL-Final-Project-
IDL final project code for apaul2, hdhingra, igoyal, sdulam

This is the code for Automatic Personality Perception using a Multimodal Coattention Network.

We have used the SSPNet Persoanlity Corpus to train our model. 
The DataPreperation file is to combine the personality scores of all the assesors as well as normalize the personality scores. 

The AudiFeatureExtraction file is to extract MFCC features. The TextFeatureExtraction file is to convert the audio to teext as well as extrace sentence embeddings. 

The Model file is the implementation of our coattention model as well as evaluating metrics. 

To each of the notebooks may be run sequentially in the order described above, once the data is downloaded. 
Since we mainly used Google Colab for this project, care should be taken to specify correct file paths. 
