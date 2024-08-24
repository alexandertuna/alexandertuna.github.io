This is a line by line breakdown of the PyTorch MNIST tutorial: https://raw.githubusercontent.com/pytorch/examples/main/mnist/main.py

Some lines are provided out of order, and this makes no difference.

# Imports

```
import argparse
import torch
import torch.nn as nn
import torch.nn.functional as F
import torch.optim as optim
from torchvision import datasets, transforms
from torch.optim.lr_scheduler import StepLR
```