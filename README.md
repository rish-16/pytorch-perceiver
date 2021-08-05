# pytorch-perceiver
PyTorch implementation of the Perceiver model by Jaegle et al. from DeepMind ([`pdf`](https://arxiv.org/pdf/2103.03206.pdf), [`abs`](https://arxiv.org/abs/2103.03206))

## Install
You can install `pytorch-perceiver` via `pip`:

```bash
pip install pytorch-perceiver
```

## Usage
You 

```python
from pytorch_perceiver import Perceiver

net = Perceiver()
x = torch.rand(128, 128, 3)
y = net(x)
```

## Contributions
If you spot anything out of line, drop an Issue or raise a PR. All ideas welcome!

## License
[MIT](https://github.com/rish-16/pytorch-perceiver/blob/main/LICENSE)