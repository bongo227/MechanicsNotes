# Elastic potential energy
Elastic potential energy is the energy stored in a spring when it is stretched/compressed past its natural length. Elastic potential energy is also a type of mechanical energy so we use it with the work-energy principals to solve complex systems with springs.

The tension in the string is given by:
$$
T = \frac{\lambda}{l}e
$$
where $$T$$ is the tension, $$\lambda$$ is the modulus of elasticity, $$l$$ is the natural length of the sprint and $$e$$ is the extension of the spring past its natural length. 

To work of the potential energy we use $$W = Fd$$, since tension is not linear we can use integration i.e. $$W = \int{F \text{ }dd}$$ to derive the potential energy of a spring
$$
\begin{align}
W &= \int^e_0{T \text{ } de}\\
&= \int^e_0{\frac{\lambda}{l}e \text{ } de}\\
&= \left[ \frac{\lambda}{l} \times \frac{1}{2}e^2 \right]^e_0\\
&= \frac{\lambda}{2l}e^2
\end{align}
$$

#### Example
The following systems spring has a natural length of $$1.25 \text{ m}$$, a modulus of elasticity of $$32 \text{ N}$$. The particle has a mass of $$0.2 \text{ kg}$$ and a coefficent of friction with the surface of $$0.3$$. Find the speed of the particle when it is $$0.6 \text{ m}$$ from the wall.
![](/assets/Capture13.PNG)

$$
\begin{align}
\text{Initial M.E.} &= \text{G.P.E.} + \text{K.E.} + \text{E.P.E.}\\
&= 0 + \left(\frac{1}{2} \times 0.2 \times 0^2 \right) + \left(\frac{32}{2 \times 1.25} \times 0.75^2\right)\\
&= 7.2 \text{ J}
\end{align}
$$

$$
\begin{align}
\text{Final M.E.} &= \text{G.P.E.} + \text{K.E.} + \text{E.P.E.}\\
&= 0 + \left(\frac{1}{2} \times 0.2 \times v^2 \right) + \left(\frac{32}{2 \times 1.25} \times -0.65^2\right)\\
&= (0.1v^2 + 5.408) \text{ J}
\end{align}
$$

$$
\begin{align}
\text{Initial M.E.} - \text{Final M.E.} &= \text{Work done against friction}\\
7.2 - (0.1v^2 + 5.408) &= (\mu R) d\\
1.792 - 0.1v^2 &= 0.3 \times (0.2 \times 9.8) \times 1.4\\
&= 0.8232\\
-0.1v^2 &= -0.9688\\
v^2 &= 9.688\\
v &= 3.11\text{ms}^{-1}\\
\end{align}
$$
