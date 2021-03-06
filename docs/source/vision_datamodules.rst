Vision DataModules
==================
The following are pre-built datamodules for computer-vision.

-------------

Supervised learning
--------------------
These are standard vision datasets with the train, test, val splits pre-generated in DataLoaders with
the standard transforms (and Normalization) values

MNIST
^^^^^

.. autoclass:: pl_bolts.datamodules.mnist_datamodule.MNISTDataModule
    :noindex:

FashionMNIST
^^^^^^^^^^^^

.. autoclass:: pl_bolts.datamodules.fashion_mnist_datamodule.FashionMNISTDataModule
    :noindex:

CIFAR-10
^^^^^^^^

.. autoclass:: pl_bolts.datamodules.cifar10_datamodule.CIFAR10DataModule
    :noindex:


Imagenet
^^^^^^^^

.. autoclass:: pl_bolts.datamodules.imagenet_datamodule.ImagenetDataModule
    :noindex:

------------

Semi-supervised learning
------------------------
The following datasets have support for unlabeled training and semi-supervised learning where only a few examples
are labeled.

Imagenet (ssl)
^^^^^^^^^^^^^^

.. autoclass:: pl_bolts.datamodules.ssl_imagenet_datamodule.SSLImagenetDataModule
    :noindex:

STL-10
^^^^^^

.. autoclass:: pl_bolts.datamodules.stl10_datamodule.STL10DataModule
    :noindex: