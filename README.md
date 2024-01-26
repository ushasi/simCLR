# simCLR
A SimCLR implementation for self-supervised learning from unlabeled data

We use the SSL4EO-S12 (just the RGB channel) unlabeled dataset to learn the pretext task and for the down-stream task, we use a subset of the Eurosat (RGB channel) data. We use the simCLR based pipeline for the self-supervised learning task.

The following are some sample images from the SSL4EO-S12 RGB dataset.

<img src=20200328T162829_20200328T164812_T15QXA.png width="100"> <img src=20200621T162901_20200621T164746_T15QXA.png width="100"> <img src=20200924T162929_20200924T164434_T15QXA.png width="100"> <img src=20201228T163711_20201228T164519_T15QXA.png width="100">

The following are some sample images from the Eurosat RGB dataset which have been used for learning the down-stream task of classification.

<img src=AnnualCrop_2.jpg width="100"> <img src=Highway_165.jpg width="100"> <img src=Industrial_172.jpg width="100"> <img src=Residential_110.jpg width="100">

The Google Colab (.ipynb) implementation of the same can be found in simCLR.ipynb file in this repository.
