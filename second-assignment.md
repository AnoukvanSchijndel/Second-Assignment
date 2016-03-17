% Numerical Simulation, March 2016

### Effects of an advertising ban

Consider two firms that produce and sell cigarettes (differentiated products).

The demand functions are:

$$
q_1=500-15p_1+5p_2+5\sqrt{A_1}-3\sqrt{A_2}
$$
$$
q_2=500+5p_1-15p_2-3\sqrt{A_1}+5\sqrt{A_2}
$$

$q_i$ denotes the quantity, $p_i$ the price per unit and $A_i$ the advertising expenditure of firm $i$, $i=1,2$.
Marginal costs are constant and equal to 2 per unit for both firms. 

Consider a (one-shot pure) Nash equilibrium in which each firm sets its own price and advertising level, conditional on the price and advertising level of the competing firm. 

a) Denote the prices, advertising levels, quantities and profits in this equilibrium.

\begin{equation}
\pi_1=(p_1-c)q_1-A_1

\pi_1=(p_1-2)(500-15p_1+5p_2+5\sqrt{A_1}-3\sqrt{A_2})-A_2
\end{equation}

First, let's solve for the equilibrium price level of firm $1$.
 
To do this, take the first order derivative with respect to $p_1$.

\begin{equation}
\frac{d\pi_1}{dp_1}=500-15p_1+5p_2+5\sqrt{A_1}-3\sqrt{A_2}+(p_1-2)*15=0
\end{equation}

Solving for $p_1$ gives:

\begin{equation}
p_1=17\frac{2}{3}+\frac{1}{6}p_2+\frac{1}{6}\sqrt{A_1}-\frac{1}{10}\sqrt{A_2}
\end{equation}

Similarly for firm 2 gives:

\begin{equation}
p_2=17\frac{2}{3}+\frac{1}{6}p_1+\frac{1}{6}\sqrt{A_1}-\frac{1}{10}\sqrt{A_2}
\end{equation}

By substituting these best-response functions into each other, we can solve for the equilibrium price levels. 

Note, that the firms are symmetric! This implies that price levels and advertisement levels of both firms are equal. 

\begin{equation}
p_1=17\frac{2}{3}+\frac{1}{6}p_1+\frac{1}{6}\sqrt{A_1}-\frac{1}{10}\sqrt{A_2}
p_1=p_2=21\frac{1}{5}+\frac{2}{25}\sqrt{A_1}
\end{equation}

Second, let's solve for the equilibrium advertisement level of firm $1$.

To do this, take the first order derivative with respect to $A_1$.

\begin{equation}
\frac{d\pi_1}{dA_1}=(p_1-2)(2\frac{1}{2}\frac{1}{\sqrt{A_1}})-1=0
\end{equation}

Solving for $A_1$ gives:

\begin{equation}
A_1=A_2=(2\frac{1}{2}p_1-5)^2
\end{equation}

Now we have 2 equations, with 2 unknowns. We can substitute the functions into each other, which will gives the solution of the equilibrium price and advertisement levels. 

The final solution is:
$p_1^*=p_2^*=26, A_1^*=A_2^*=3600, q_1^*=q_2^*=360 & \pi_1^*=\pi_2^*=5040$

b) Investigate the effects of a ban on cigarette advertising. Explain (in words) why an advertising ban can increase profits. 

Now firms can only determine their prices. 

To determine the new price level, take the first order derivative with respect to price. 

\begin{equation}
\frac{d\pi_1}{dp_1}=500-15p_1+5p_2+(p_1-2)*-15=0
\end{equation}

Solving for $p_1$ gives:

\begin{equation}
p_1=17\frac{2}{3}+\frac{1}{6}p_2
\end{equation}

Similary for firm 2:

\begin{equation}
p_2=17\frac{2}{3}+\frac{1}{6}p_1
\end{equation}

Substituting these best-reponse functions into each other will give the equilibrium price level. 

Note that firms are symmetric!

\begin{equation}
p_1=17\frac{2}{3}+\frac{1}{6}p_1
\end{equation}

Solving for $p_1$ gives:

\begin{equation}
p_1^*=p_2^*=21.20
\end{equation}

Next solve for the equilibrium quantities and profits.

\begin{equation}
q_1^*=q_2^*=288 & \pi_1^*=\pi_2^*=5530
\end{equation}

The results show that when firms are not any longer allowed to advertise they can actually achieve higher profits!
On the one hand, the advertisement ban decreases demand and therefore profits. On the other hand, firms will decrease their prices which gives upward pressure on demand and profits. If the price decrease is high enough it will offset the downward pressure on profits and might even increase profits. 