### AI Generated VS Real Image Classification CIFAKE

Two custom deep learning models built from scratch to classify real and AI-generated images using the CIFAKE dataset (120,000 images, 32×32 RGB). No pre-trained weights used.

Models: Custom Deep CNN with Flexible Kernels (94% accuracy) and Custom Deep Multi-Dense Network (79.5% accuracy). Both tuned using Optuna Bayesian hyperparameter optimisation across 100 trials.

Dataset: dragonintelligence/CIFAKE-image-dataset on HuggingFace. Download automatically via the datasets library.

To run: install dependencies, load the dataset through HuggingFace, execute the preprocessing notebook, train each model using the provided training functions, tune using the Optuna objective functions, then run inference on the test set.
