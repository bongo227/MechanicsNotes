# Integrating
Given the fact that we can differentiate to get velocity and accelerations, it follows that we can integrate to "go backwards".

#### Example
At time $$t = 0$$, an object sets off from the rest at the origin, $$O$$, and travels along the x-axis. At the time $$t$$ seconds, the object is accelerating at the rate of $$(2t - 4) \text{ ms}^{-2}$$ Find the time it takes to return to the point $$O$$.

###### Integrate to find the displacement
$$
\begin{align}
a &= 2t - 4\\
v &= \int{a \text{ }dt} = t^2 - 4t\\
s &= \int{v \text{ }dt} = \frac{1}{3}t^3 - 2t^2
\end{align}
$$
Not we can eliminate the constants of integration since we know the acceleration is zero when the time is zero and that the displacement is zero when time is zero.

###### Find the point where the displacement is zero
$$
\begin{align}
\frac{1}{3}t^3 - 2t^2 &= 0\\
t^2 \left(\frac{1}{3}t - 2\right) &= 0\\
t &= 0, 6\\
t &= 6
\end{align}
$$