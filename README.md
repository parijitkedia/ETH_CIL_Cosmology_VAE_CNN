Here we propose a method of generating and scoring cosmological images, using a Variational Auto-Encoder (VAE) and a Convolutional Neural Network (CNN) respectively. We use a dataset that has a varying range of similarity scores to a ”prototypical cosmology image” and one with positive and negative examples of cosmology images. With these two datasets we were able to generate thousands of images resembling real galaxies and achieve a score of 0.63485 on the Kaggle leaderboard. The VAE proved to be highly sensitive to parameter tuning, however within a certain range of hyperparameters and training method, the outcome was superior. The results were compared to the output of a Deep Convolutional Generative Adversarial Network (DCGAN) and the CNN far outperformed the DCGAN in learning similarity scores.

We received a competitive grade of 5.63 and a final grade of 5.326 for this work, on a 6 point scale.