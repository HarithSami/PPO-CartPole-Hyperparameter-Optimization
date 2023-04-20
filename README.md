
# CartPole Hyperparameter Optimization
This Jupyter Notebook is an implementation of hyperparameter optimization for the CartPole-v1 environment using the PPO algorithm from the Stable Baselines3 library.

The hyperparameters that are being optimized are the learning rate, n_steps, batch size, gamma, and gae_lambda. The hyperparameters can be modified in the code to test different values for these parameters.

The notebook runs a loop of 10000 iterations and saves the results to a CSV file named "{environment_name}_{algorithm_name} GAE Lambda and GAMMA testing at 12500.csv". The CSV file includes the iteration number, learning rate, batch size, gamma, gae_lambda, and mean score for each iteration.

The code also saves the trained model for each iteration to the directory "Training/Saved Models/hyperparam testing".

The code also calculates the mean score and standard deviation of the last 50 episodes for each iteration and prints them out.

To run the code, simply modify the hyperparameters in the code as required and run the notebook. The results will be saved to the CSV file mentioned above.
