Please run in sequence.

In the first part, all input values should be torch.tensor. The optimal_control() function can only accept t_batch values without duplicates. Default parameters are provided as in the Piazza post.

In the second part, execution is relatively slow, so default parameters batch_size and num_epochs are kept small.

In the third and fourth parts, the two neural networks are initially run together, followed by model training.
In the third part, 100 sets of random t and x are generated as test data, and the difference between Deep Galerkin and Monte Carlo solutions is compared.

Except for the fourth part, all loss calculations are either square error or mean square error.
