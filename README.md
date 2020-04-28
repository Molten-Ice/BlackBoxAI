# Black Box AI
Simple deep learning framework

## Overview

### Built With

* [PyTorch](https://pytorch.org/)
### Authors

* **James Davey** - *head of technology at* [WarwickAI](https://warwickai.ml/)

## Updating github

Firstly, To push this remote branch to your github branch use the code

```python
git add .
git commit -m "Commit message"
git push -u origin dev
```


Secondly, we want to merge all the changes from our `dev` branch into the `master`.

```python
(on branch development)$ git merge master
(resolve any merge conflicts if there are any)
git checkout master
git merge development (there won't be any conflicts now)
git pull
```

## Papers

### Initialization

* [Kaiming](https://arxiv.org/abs/1502.01852)
* [Xavier](http://proceedings.mlr.press/v9/glorot10a.html)

### Misc

* [Fixup Initialization: Residual Learning Without Normalization](https://arxiv.org/abs/1901.09321)
* [Self-Normalizing Neural Networks](https://arxiv.org/abs/1706.02515)
* [Exact solutions to the nonlinear dynamics of learning in deep linear neural networks](https://arxiv.org/abs/1312.6120)
* [All you need is a good init](https://arxiv.org/abs/1511.06422) - iteratively set weights
