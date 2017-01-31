# Center of mass
The center of mass is the point in which all the objects weight acts through.

## Particles in a line
To find the center of mass for particles on a strait line we use the following formula
$$
\sum{mx} = \bar{x}\sum{m}\\
\sum{my} = \bar{y}\sum{m}
$$
where $$m$$ is the mass of the particle, $$x$$ and $$y$$ is the distance between a chosen point and $$\bar{x}$$ and $$\bar{y}$$ is the distance between the chosen point and the center of mass.

#### Example
![](/assets/Capture5.PNG)
Find the distance of the center of mass from $$O$$

$$
\begin{align}
(1 \times 0.5 + 4 \times 1.4 + 3 \times 2.0) &= \bar{x} \times (1 + 4 + 3)\\
12.1 &= \bar{x} \times 8\\
\bar{x} &= 1.5125
\end{align}
$$

## Particles in two dimensions
The method above can be extended into 2-dimensions with the formula
$$
\sum{m \pmb{r}} = \bar{\pmb{r}} \sum{m}
$$
where $$\pmb{r}$$ is the position vector of each particle from a chosen point, and $$\bar{\pmb{r}}$$ is the position vector of the center of mass of the particles.

#### Example
![](/assets/Capture6.PNG)
Find the coordinates for the center of mass

$$
\begin{align}
\left(
2 \times \begin{pmatrix} 1 \\ 2 \end{pmatrix} + 
8 \times \begin{pmatrix} 2 \\ 3 \end{pmatrix} + 
6 \times \begin{pmatrix} 6 \\ 4 \end{pmatrix}\right) &= 
\begin{pmatrix} x \\ y \end{pmatrix} \times
(2 + 8 + 6)\\

\begin{pmatrix} 54 \\ 54 \end{pmatrix} &= 
\begin{pmatrix} x \\ y \end{pmatrix} \times 16\\

\begin{pmatrix} x \\ y \end{pmatrix} &=
\begin{pmatrix} \frac{27}{8} \\ \frac{13}{4} \end{pmatrix}

\end{align}
$$
