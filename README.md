# Feedback Alignment With Weight Normalization

These source codes are provided for re-generating all figures of the following work (available [here](https://www.biorxiv.org/content/10.1101/2021.06.12.447639v1.abstract)):

> RahmanSetayesh, Alireza, Ali Ghazizadeh, and Farokh Marvasti. "The underlying mechanisms of alignment in error backpropagation through arbitrary weights" bioRxiv (2021).

The strategy in all of these codes is to save results in a directory and then load the results for plotting the figures.

You need to change preamble of each notebook to save results and figures in your desired path ("base_directory_str").

These notebooks were run on google colab. Based on your runtime environment you may need to make some changes to the preamble of each notebook and also add modules in my_modules folder to python path.

We used PyTorch library only for accelerating computations on GPU. We did not use PyTorch's automatic differentiation capability. 

Any feedback is welcome. Please email me (alireza.setayesh77@gmail.com) or send issues/pull requests, if you have any feedback.
