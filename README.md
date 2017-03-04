# Pytorch Highway network

[Highway network](https://arxiv.org/abs/1505.00387) implemented in [PyTorch](http://www.pytorch.org).

![Highway Equation](images/highway.png)

## Usage

```python
highway = Highway(input_size, num_layers, f=torch.nn.functional.relu)

# input is [batch_size, input_size] shaped tensor
out = highway(input)
```