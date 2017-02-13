# Differential equations
If we have a varible acceleration caused by an overall force we can use differential equatiosn to describe the bodys motion: $$F = m\frac{dv}{dt}$$.

#### Example
At time $$t = 0$$ seconds, a mass of 5 kg begins to fall downwards. Their is a restive force of 4v N. Find v in terms of t.

###### Use newtons second law
$$
\begin{align}
F &= ma\\
5g - 4v &= 5 \times \frac{dv}{dt}\\
g - \frac{4}{5}v &= \frac{dv}{dt}\\
\frac{1}{g - \frac{4}{5}v} &= \frac{dt}{dv}\\

\int{\frac{1}{g - \frac{4}{5}v} \text{  } dv} &= \int{\frac{dt}{dv} \text{  } dv}\\
-\frac{5}{4}\ln\left|g - \frac{4}{5}v\right| + c &= \int{dt}\\
-\frac{5}{4}\ln\left|g - \frac{4}{5}v\right| &= t + C\\
\end{align}
$$

###### Solve the constant of integration
When $$t = 0$$, $$v = 0$$ so:
$$
\begin{align}
-\frac{5}{4}\ln|g| &= C\\

\end{align}
$$

###### Simplify
$$
\begin{align}
-\frac{5}{4}\ln\left|g - \frac{4}{5}v\right| &= t -\frac{5}{4}\ln|g|\\
\ln\left|g - \frac{4}{5}v\right| &= -\frac{4}{5}t + \ln|g|\\
g - \frac{4}{5}v &= e^{-\frac{4}{5}t + \ln|g|}\\
g - \frac{4}{5}v &= e^{-\frac{4}{5}t} \times e^{\ln|g|}\\
g - \frac{4}{5}v &= ge^{-\frac{4}{5}t}\\
-\frac{4}{5}v &= ge^{-\frac{4}{5}t} - g\\
v &= -\frac{5}{4}g(e^{-\frac{4}{5}t} - 1)\\








\end{align}
$$