# ASKEW: Perspective transform along specified axes

## Original Author

Hou-Ning Hu / [@eborboihuc](https://eborboihuc.github.io/)

## Prerequisites

[The original repo](https://github.com/eborboihuc/rotate_3d)

This version is made for:
- Python3
- with numpy
- with OpenCV

## Usage

```python
import askew3

it = askew3.ImageTransformer(img_path, height=height, width=width)
it.skew(theta=0, phi=0, gamma=0, dx=0, dy=0, dz=0) # optional bg = (0,0,0) for background color (supply triplet)
it.save(new_img_path)
```
