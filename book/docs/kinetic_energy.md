---
jupytext:
  formats: md:myst
  text_representation:
    extension: .md
    format_name: myst
kernelspec:
  display_name: Python 3
  language: python
  name: python3
---

# Kinetic Energy

Here is a plot of the kinetic energy of an object with a mass of 5 kg against its velocity

```{code-cell}
import numpy as np
import matplotlib.pyplot as plt

v = np.arange(0, 11)
v_squared = v**2
```
