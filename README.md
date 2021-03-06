## Generative model experiments

This repo contains miscellaneous code / experiments relating to generative latent variable models (and how these might relate to aspects of memory).

The code here is Python written in Jupyter Notebooks.

### Contents:

- types_of_model - these notebooks implement several types of generative model trained on the MNIST handwritten digits dataset, using TensorFlow / Keras
  - mnist_vae.ipynb - a variational autoencoder
  - mnist_gan.ipynb - a generative adversarial network
  - mnist_aae.ipynb - an adversarial autoencoder
- memory_distortions - notebooks modelling memory distortions in this type of model (work in progress)
  - carmichael_expt_vae_with_context.ipynb - a notebook modelling the results of Carmichael (1932) regarding contextual effects on memory distortion
  - news_article_DRM_VAE_expt_one.ipynb - a model of semantic intrusion in the recall of word lists, working towards a model of the Deese-Roediger-McDermott task
- misc_nlp_notebooks: miscellaneous natural language processing notebooks
  - seq2seq_recurrent_autoencoder.ipynb - character level autoencoder for text
  - sentence_vae_attempt_one.ipynb - unsuccessful attempt at VAE for sentences
  - text_generation_rnn.ipynb - this slightly altered copy of TensorFlow tutorial notebook trains an RNN to generate news articles 
