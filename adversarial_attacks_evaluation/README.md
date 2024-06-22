## Generating Adversarial Examples
An FGSM attack was applied on the data set [deepfake and real images](https://www.kaggle.com/datasets/manjilkarki/deepfake-and-real-images), based on the [OpenForensics: Multi-Face Forgery Detection And Segmentation In-The-Wild Dataset](https://zenodo.org/records/5528418#.YpdlS2hBzDd). Parameters used were an epsilon value of 0.05 and a norm of 2.

See [the notebook](transformer-attack.ipynb) for our implementation of applying FGSM on the dataset and saving the resulting adversarial examples.

The implementation for FGSM was imported from the CleverHans library implementation of FGSM found [here](https://github.com/cleverhans-lab/cleverhans/blob/master/cleverhans/torch/attacks/fast_gradient_method.py).
