# UnsupervisedDomainAdaptation

Requirements:
 - Create in the same folder of the scripts, a folder "log" to save the files to display the TensorBoard.
 - Create in the same folder of the scripts, a folder "checkpoint" to save the files to save the checkpoint and then run them in the evaluation
 - Hyperparameters can be set in train.py in the paraameter dict.
 - After each training the checpoint.pth files are saved so to run the test on that model you should save that files with different names and then change      the name of the file in eval.py accordingly to make the paths match.
 - Few commented parts were written for debugging purposes and trying few other things.
