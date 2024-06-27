Maxwell's equations
```math
\triangledown \times \mathbf{E} = -\frac{\partial \mathbf{H}}{\partial t}; \, \,\, \triangledown \times \mathbf{H} = \frac{\partial \mathbf{E}}{\partial t};
```

in 2D with starting condition $\mathbf{H} = (0, 0, H_z)$ have the following form:

```math
\frac{\partial E_x}{\partial t} = \frac{\partial H_z}{\partial y}; \,\,\, \frac{\partial E_y}{\partial t} = -\frac{\partial H_z}{\partial x}; \,\,\, \frac{\partial H_z}{\partial t} = \frac{\partial E_x}{\partial y} - \frac{\partial E_y}{\partial x};
```
Numerical simulation example:

![alt text](https://github.com/danis-b/Maxwell_2D/blob/main/animation.gif)
