# adInfoHRL

This repository contains a Keras implementation of Hierarchical Reinforcement Learning via Advantage-Weighted Information Maximization (adInfoHRL).
A Keras implementation of TD3 is also contained.

## Requirements
gym == 0.9.1 \
mujoco_py == 0.5.7 \
numpy == 1.14.5 \
Keras == 2.1.5 \
tensorflow == 1.10.0 \
tensorflow_gpu == 1.10.0

## How to run the code
To see the performance of a policy trained on the Walker2D-v1, run
```
python demo_model_adInfoHRL.py 
```
To train a policy on HalfCheetah-v1 with adInfoHRL, run
```
python adInfoHRL.py --env HalfCheetah-v1
```
To train a policy on HalfCheetah-v1 with TD3, run
```
python TD3_keras.py --env HalfCheetah-v1
```
