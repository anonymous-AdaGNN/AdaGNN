# AdaGNN
Open-source code for ''Graph Neural Networks withAdaptive Frequency Response Filter''.

## Environment
Experiments are carried out on a Titan RTX with Cuda 10.1.

## usage
Default parameter settings are an 8-layered AdaGNN-S model.
Use as
```
python main.py
```
Pre-trained models on BlogCatalog can be found in pre_trained_examples.

Configure as you like:
```
python main.py --layers 8 --mode s --dataset Flickr --hidden 128 --dropout 0.1
```
