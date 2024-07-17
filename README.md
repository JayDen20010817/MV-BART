

![image](introduction.png)
 <br />
For obtaining the data for the framework,  please follow the steps:

Detailed steps: 
1. First install the dependencies mentioned in the dependencies.txt.
2. Second store the dataset according to the specified path.

	MUStARD dataset--link:
	Text data - It is available at https://github.com/soujanyaporia/MUStARD in data/sarcasm_data.json location. We also provide train, valid and text dlog ids with them. <br />
	Audio data - We first obtain raw video from https://github.com/soujanyaporia/MUStARD and convert those videos to audio format corresponding to the last utterance   of every dialog. The we proceed to obtain audio features in the same manner as described in https://github.com/thuiar/MIntRec/tree/main/tools/audio_preprocess.py <br />
	Video data - We get raws videos from https://github.com/soujanyaporia/MUStARD and obtain the video features corresponding to last utterance from https://github.com/soujanyaporia/MUStARD under Run the code section point 3 Download the pre-extracted visual features. <br />
	Memotion dataset--link: https://github.com/terenceylchow124/Meme-MultiModal?tab=readme-ov-file <br />
	UR-FUNNY dataset--link:   https://github.com/ROC-HCI/UR-FUNNY?tab=readme-ov-file <br />


3. Finally run framework_drive.ipynb、framework_drive_ablation_T-A view.ipynb、framework_drive_ablation_T-A-V view.ipynb、framework_drive_ablation_T-V view .ipynb
4. （Low resource migration testing can be conducted by setting the training size in the framework_drive.ipynb file）


![image](framework.png)
