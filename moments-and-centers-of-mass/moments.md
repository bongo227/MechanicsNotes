# Moments

A moment is a turning force about a point expressed by a $$m = Fd$$ where $$m$$ is the moment $$F$$ is the magnitude of the force and $$d$$ is the distance from the pivot.

If more that one force is acting on the pivot we must add all the moments to find the total moment about that point. If the sum of the moments equals zero then the pivot will be at **equilibrium** (it won't rotate).

If the forces are acting in opposite directions make one direction positive and the other negative then sum the moments the same way.

#### Example
![](/assets/Capture.PNG)
Given that the sum of the moments is $$3\nm$$ find the value of $$\theta$$.

$$
\begin{align}
(-7 \times 6) + (9\cos(\theta) \times 1) + (27\sin(\theta) \times 3) &= 3\\
-35 + 9\cos(\theta) + 81\sin(\theta) &= 3\\
90\sin(\theta) &= 45\\
\sin(\theta) &= \frac{1}{2}\\
\theta &= \frac{1}{6}\pi\\
\end{align}
$$

## "Ladder" questions

"Ladder" questions occur when a rigid body rest against the wall and ground. The wall or ground may be rough so you may need to account for friction using: $$F = \mu R$$.

#### Example 1
A ladder of mass 9kg and length 4.8m rests in limiting equilibrium against a rough wall on a rough ground. The normal reaction against the wall is 22N, and 75N against the ground. Find the angle that the ladder makes with the ground. 

![](/assets/Capture3.PNG)

###### Resolve horizontally
$$
F_G = 22\n
$$

###### Resolve vertically
$$
\begin{align}
75 + F_W &= 9g\\
F_W &= 13.2\n
\end{align}
$$

###### Moments about the base of the ladder
$$
\begin{align}
9g\cos(\alpha) \times 24 &= (22\sin(\alpha) \times 4.8) + (13.2\cos(\alpha) \times 4.8)\\
148.32\cos(\alpha) &= 105.6\sin(\alpha)\\
\tan(\alpha) &= 1.4045...\\
\alpha &= 54.6^\circ
\end{align}
$$

###### Coefficent of friction between wall and the ladder
$$
\begin{align}
F_W &= \mu R\\
13.2 &= \mu \times 22\\
\mu &= \frac{13.2}{22} = 0.6\\
\end{align}
$$

###### Coefficent of friction between ground and the ladder
$$
\begin{align}
F_G &= \mu R\\
22 &= \mu \times 75\\
\mu &= \frac{22}{75} = 0.29\\
\end{align}
$$

#### Example 2
A uniform ladder of mass 10 kg and length 6 m rests with one end on rough, horizontal ground and the other end against a smooth, vertical wall. The coefficient of friction between the ground and the ladder is 0.3, and the ladder makes an angle of 65° with the ground. How far can the 50kg object move up the ladder before it slips

![](/assets/Capture4.PNG)

###### Resolve vertically
$$
\begin{align}
R &= 10g + 50g\\
&= 588\n
\end{align}
$$

###### Find $$N$$
$$
\begin{align}
N &= F = \mu R\\
&= 0.3 \times 588\\
&= 176.5\\
\end{align}
$$

###### Moments about base
$$
\begin{align}
176.5\sin(65) \times 6 &= 10g \times \cos(65) \times 3 + 50g \times \cos(65) \times x \\
x &= 4.03
\end{align}
$$
