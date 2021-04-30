# DANet

This is our implementation for the paper:

*DANet: Deformable Attentive Network for Deep Reinforcement Tracking Approach*




## Environments

- python 3.8
- pytorch 1.4.0
- ninja 1.9.0
- numpy 1.18.1


## Example to run the codes		


The implemention of data preprocessing is modified based on *[this](https://github.com/visionml/pytracking)*


Run our tracker:

```
python run_tracker.py atom default --dataset otb --sequence Basketball --debug 1 --threads 0
```




