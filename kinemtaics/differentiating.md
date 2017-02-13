# Differentiating
Velocity is the rate of change of displacement, so if you had a function for displacement in terms of time you could differentiate it to find its velocity. Similarly velocity differentiates into acceleration.

#### Example
A train travels along a strait track between two stations. The train is at rest at both of these stations. At time $$t$$ hours, the trains distance from the station is given by $$s = (90t^2 - 45t^3) \text{ km}$$. Find the maximum speed of the train between the two stations.

###### Find the derivative of velocity
$$
\begin{align}
s &= 90t^2 - 45t^3\\
v &= \frac{ds}{dt} = 180t - 135t^2\\
\frac{dv}{dt} &= 180 - 270t
\end{align}
$$

###### Find the stationary point
$$
\begin{align}
180 - 270t &= 0\\
-270t &= -180\\
t &= \frac{180}{270}\\
&= \frac{2}{3}\\
\end{align}
$$

###### Find the velocity
$$
\begin{align}
v &= 180t - 135t^2\\
&= 180 \times \frac{2}{3} - 135 \times \left(\frac{2}{3}\right)^2\\
&= 60 \text{ kmh}^{-1}
\end{align}
$$