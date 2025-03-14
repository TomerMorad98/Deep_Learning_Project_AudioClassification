CNN14 model 
Refer to: "cnn14_model\CNN14.ipynb"

predictions: 
For using the model please run all the cells except the MAIN cell ( which will re-Train the model ) , the last cell is dedicated for predictions.

- if you wish to predict audio not from the Audio folder :

•	Please create a new folder with your desired audio files, and in the DEFINITIONS cell 		switch the path of the AUDIO_DIR .
•	CSV_UNCLEANED_PATH is a CSV with the list of audio files, use this as a template to 		switch to a new csv file with your desired audio file,
•	If the audio files are inside AUDIO_DIR, the  processing will be made automatically
•	After running the PREDICTION USING THE MODEL block, you will see a new column in your 		csv file which has the predictions. 

AST model 
Refer to "ATS.ipynb"

- if you wish to predict audio not from the Audio folder :
	follow the same steps ( do not run Training - will train a model from the start 
	in the first cell - 
	sample_dir <=> AUDIO_DIR
	label_csv <=> CSV_UNCLEANED_PATH
