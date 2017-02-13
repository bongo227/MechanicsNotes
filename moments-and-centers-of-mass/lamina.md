# Lamina
Lamina are shapes with an mass spread evenly across their surface. The center of mass is always at the intersection of the lines of symmetry. Loaded lamina are lamina with a mass attached, to find the center of mass find the lamina center of mass, then you can treat the system as two or more particles.

#### Example
The following lamina has a mass of $$5\text{ kg}$$. A $$1\text{ kg}$$ mass is attached at $$O$$, find the center of mass.

![](/assets/Capture7.PNG)

###### Find the lamina's center of mass
Let $$A$$ be the 2x1 rectangle at the top, $$B$$ the 1x1 square in the middle and $$C$$ the 1x5 rectangle on the left.

$$
\begin{align}
A + B + C &= (2 \times 1) + (1 \times 1) + (1 \times 5)\\
&= 2 + 1 + 5\\
&= 8\text{ cm}^2\\
\end{align}
$$

$$
\begin{align}
5 \times \frac{2 \times 1}{8} \times \begin{pmatrix} 2 \\ 4.5 \end{pmatrix} + 
5 \times \frac{1 \times 1}{8} \times \begin{pmatrix} 1.5 \\ 2.5 \end{pmatrix} +
5 \times \frac{5 \times 1}{8} \times \begin{pmatrix} 0.5 \\ 2.5 \end{pmatrix} &=
\begin{pmatrix} x \\ y \end{pmatrix} \times 5\\

\begin{pmatrix} 2.5 \\ 5.625 \end{pmatrix} + 
\begin{pmatrix} 0.9375 \\ 1.5625 \end{pmatrix} + 
\begin{pmatrix} 1.5625 \\ 7.8125 \end{pmatrix} &= 
\begin{pmatrix} 5 \\ 15 \end{pmatrix} \times 5\\

\begin{pmatrix} x \\ y \end{pmatrix} &= \begin{pmatrix} 1 \\ 3 \end{pmatrix}\\
\end{align}
$$

###### Find the overall center of mass
$$
\begin{align}
1 \times \begin{pmatrix} 0 \\ 0 \end{pmatrix} + 5 \times \begin{pmatrix} 1 \\ 3 \end{pmatrix} &= \begin{pmatrix} x \\ y \end{pmatrix} \times (1 + 5)\\
\begin{pmatrix} x \\ y \end{pmatrix} &= \begin{pmatrix} \frac{5}{6} \\ \frac{15}{6} \end{pmatrix}
\end{align}
$$