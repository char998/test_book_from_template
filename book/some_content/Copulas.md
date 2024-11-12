```{code} python
:label: my-program
:caption: Creating a TensorMesh using SimPEG
from discretize import TensorMesh

hx = [(1, 40)]
hy = [(1, 40)]

mesh = TensorMesh([hx, hy])
```

In the [](#my-program), we create a mesh for simulation using [SimPEG](https://discretize.simpeg.xyz/).