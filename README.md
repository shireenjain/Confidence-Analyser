# Confidence-Analyser

This project aims to develop a machine learning model that can accurately gauge a speaker's level of confidence during public speaking by analyzing their non-verbal cues, including body language, facial expressions, posture, and gestures. The model assigns weights to these parameters and provides scores for each, which are used to classify the video as to whether the speaker is confident or not. The proposed solution is oriented towards interview readiness and addresses the need for effective evaluation methods in online interview-oriented environments.


## Usage

1. Input various classes to be detected through the `modularAdd.py` script.
2. Train the model on the newly added dataset using `model_train.py`.
3. Run the prediction engine to see the results in realtime.
