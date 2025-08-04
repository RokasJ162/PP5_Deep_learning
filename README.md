# In this program I have automated the tuning process by including a function that determines the optimal neuron count.
# During the tuning I have came to the conclusion that 'adam' optimizer is far more suitable for this kind of problem.
# It is worth mentioning that Keras functional API was updated due to the fact that 'input_shape' argument is expected to be deprecated in the future.

# Results with adam optimizer:
# Neurons: 16, Average MAE: 4.89
# Neurons: 32, Average MAE: 6.25
# Neurons: 64, Average MAE: 11.57
# Neurons: 128, Average MAE: 14.97
# Optimal number of neurons: 16 (Average MAE: 4.89)

# Results with rmsprop opimizer:
# Neurons: 16, Average MAE: 5.38
# Neurons: 32, Average MAE: 5.58
# Neurons: 64, Average MAE: 8.76
# Neurons: 128, Average MAE: 11.35
#
# Optimal number of neurons: 16 (Average MAE: 5.38)

# Evaluation results:
# Neurons: 16, Average MAE: 4.83
