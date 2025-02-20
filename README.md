# chaos-doubling
Transition to Chaos through Period-Doubling Bifurcations in Maps, ODEs and PDEs

## Logistic Map

$$
\begin{align}
  x_{n+1} = r x_n (1-x_n)
\end{align}
$$

Bifurcation diagram
![logisticbifurcation](https://user-images.githubusercontent.com/72228598/189374873-1a315094-5f96-4bca-a024-70d492af3421.png)



## Ordinary Differential Equations - Feigenbaum System

$$
\begin{align}
  &\dot{x} =a y \\
  &\dot{y} = x + z^2 \\
  &\dot{z} = b + cx + dz 
\end{align}
$$

Period-doubling
![RK4doubling2](https://user-images.githubusercontent.com/72228598/189376488-70e98ef0-1636-41cc-ba5b-e24b11411188.png)


Bifurcation diagram for component y
![y(c)](https://user-images.githubusercontent.com/72228598/189374406-4c1b28c9-2d65-4fe9-b017-210944abfce4.png)


## Partial Differential Equations - Kuramoto-Sivashinsky Equation

$$
\begin{align}
  \frac{\partial u}{\partial t} = -u\frac{\partial u}{\partial x} - \frac{\partial^2 u}{\partial x^2} - \nu \frac{\partial^4 u}{\partial x^r}
\end{align}
$$

Periodic
![KS_periodic3D](https://user-images.githubusercontent.com/72228598/189374652-d3d290cb-900f-43b9-a11c-c57a3a47b8b2.png)


Chaotic
![KS_chaotic3D](https://user-images.githubusercontent.com/72228598/189374590-d01366ed-11bc-4069-9635-ba6f0caf072d.png)


Transition from Periodic to Chaotic
![KSbifurcation](https://user-images.githubusercontent.com/72228598/189374746-dd51b591-12fc-4763-889d-05740b7026e8.png)

---
This toolbox comes as support for the conference proceeding: [Transition to chaos through period doubling bifurcations in maps, ODEs and PDEs](https://doi.org/10.1063/5.0150575)
Cite as: G. T. Pana V. Baran and A. Nicolin, Transition to chaos through period doubling bifurcations in maps, ODEs and PDEs, AIP Conf. Proc. 2843, 050008 (2023), https://doi.org/10.1063/5.0150575.
