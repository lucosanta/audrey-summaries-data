# Master Thesis report data using AUDREY and Tensorboard
In this repositories, I will put the summaries and related video which comes from AUDREY.

## Summaries

In this repository are placed all the experiment done during Master Thesis. They will be organized for DeepTesla experiment and TORCS experiment.

Currently, Tensorboard summaries available are:
  * NVIDIA - DeepTesla
  * CNN LSTM - DeepTesla
  * NVIDIA - [CARLA data](https://github.com/carla-simulator/carla)](https://github.com/carla-simulator/carla)
  * CNN LSTM - [CARLA data](https://github.com/carla-simulator/carla)
  * A3C - [CARLA data](https://github.com/carla-simulator/carla)
  
### Install Tensorboard
I assume you have Python3 installed.

First of all, install [Tensorflow](https://www.tensorflow.org/install/). For this thesis, it has been used Tensorflow 1.3.

Open a terminal and type:

```
$ sudo pip3 install tensorboard
```

### Show data

Once `pip3` has finished to install, open a terminal and type
```
$ cd audrey-summaries-data/summaries/

$ tensorboard --logdir=<summary_folder>/
```

## Experiment video







