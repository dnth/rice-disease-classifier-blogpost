# How to use Transformer to Classify Rice Leaf Diseases with TIMM and Fastai

This is an accompanying repo for the blog post How to use Transformer to Classify Rice Leaf Diseases with TIMM and Fastai. Link to the full blog post


In this blog post, I will walk you through how to use the Timm library to train a state-of-the-art deep learning model with Fastai to classify rice leaf diseases.

Among the things you will learn:

* Installation of the libraries.
* Prepare and label any dataset for object detection.
* Train a high-performance mobilevit model with Timm & Fastai.
* Monitoring training with weights and biases.
* Use the model for inference on new images.

By the end of the post, you will have a classifier model that will automatically classify rice leaf disease an image.

`pip install fastai`

`pip install timm`

`pip install jupyterlab`

`pip install git+https://github.com/rwightman/pytorch-image-models.git`

`pip3 install torch torchvision --extra-index-url https://download.pytorch.org/whl/cu113`


Data from

https://www.kaggle.com/datasets/tedisetiady/leaf-rice-disease-indonesia

TEDI SETIADY Southeast Sulawesi, Indonesia.

Link to experiment
https://wandb.ai/dnth/leaf-disease-blogpost?workspace=user-dnth