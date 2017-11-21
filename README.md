# CosmoFlow

How to run:
step 0: If at NERSC, load the tensorflow module: module load tensorflow. 

step 1: Change the hyper parameters in hyper_parameters_Cosmo.py (see the notations in the python script)

step 2: python CosmoNet_noFeed.py
output data:
	losses.txt: the loss as a function of epoch
	loss_train.txt: the relative error for training data
	loss_val.txt: the relative error for validation
	loss_test.txt: the relative error for test data
	test_batch_X.txt: the file to store the predicted and the ground true ([\Omega_m_true \Sigma_8_true \Omega_m_predicted \Omega_m_true])
	best model information: best_validation.meta, best_validation.index, best_validation.data-00000-of-00001 
