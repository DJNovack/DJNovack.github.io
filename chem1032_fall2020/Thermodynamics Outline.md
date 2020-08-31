# Thermodynamics

Recall that **thermodynamics** is the study of the relationship between work and energy in chemical and physical processes.

### Spontaneity
Thermodynamic favorability determines whether a process is **spontaneous**, occurs naturally under given conditions, or **non-spontaneous**, energy must be input into the system for the process to occur.

### Entropy
A **reversible process** is one that occurs so slowly that it is always at equilibrium. Originally introduced to describe spontaneous heat flow, **entropy (S)** change was introduced as;


$$ \Delta S = \frac {q_{rev}}{T} $$
<br/>

*Ludwig Boltzmann* came up with a statistical formulation, having to do with the amount of *microstates(W)* possible for a system. A **microstate** is a specific microscopic configuration of energies and positions of a system. Boltzmann's entropy is defined as;

$$ S = klnW $$
<br/>

where k is Boltzmanns constant,$ 1.38 \times 10^-23\ J/K$. Since entropy is a state function, the entropy change can be defines as;

$$ \Delta S = kln\frac {W_f}{W_i} $$
<br/>

Where $W_i$ and $W_f$ are the respective initial and final number of microstates of a system.

Considering a system of N particles with n boxes, the amount of possible microstates would be $n^N$. Microstates with equivalent particle arrangements are called *distributions*, where the most probable distribution is the one with the largest entropy.

![image.png](attachment:image.png)

### Second Law of Thermodynamics

For a spontaneous process, the entropy of the universe must increase.

$$ \Delta S_{uni} = \Delta S_{sys} + \Delta S_{surr} $$
<br/>

### Third Law of Thermodynamics

The entropy of a pure, crystalline solid a 0 K is 0.

### Free Energy

The **Gibbs Free Energy (G)** is another thermodynamic property that allows us to define sponteneity only though consideration of the system.

$$ G = H\ - TS $$
<br/>

Again, the Gibbs free energy is a state function and as such can be described through changes in the respective enthalpy and entropy.

$$\Delta  G = \Delta H\ - T\Delta S $$

While maybe not immediatly straightforward, the Gibbs energy can be derived;

$$ \Delta S_{uni} = \Delta S_{sys} + \Delta S_{surr} $$


$$ \Delta S_{uni} = \Delta S_{sys} + \frac{q_{surr}}{T} $$

<br/>
recall that at $q_{surr}$ = $-q_{sys}$ and at constant p, $\Delta H = q_{sys}$;

$$ \Delta S_{uni} = \Delta S_{sys} - \frac{ \Delta H}{T} $$

$$ -T \Delta S_{uni} = \Delta H - T \Delta S_{sys} $$

$$\Delta  G = \Delta H\ - T\Delta S $$

Thus, we can now use this new concept to define sponteneity in terms of the system.

|$\Delta S_{uni}$ | $\Delta  G$  | Spont.?  | 
|---|---|---|
|$\Delta S_{uni} > 0$ | $\Delta  G < 0$   | yes|   
|$\Delta S_{uni} < 0$ | $\Delta  G > 0$   | no |   
|$\Delta S_{uni} = 0$ | $\Delta  G = 0$   | equilibrium | 

This difference in G could also be throught of as the summation of energy produced v. the energy lost to surroundings, the Gibbs energy is thus the energy available to do work.

### Calculating Free Energies

<br/>
Free energies can be calculated using Hess's law, as was done with enthalpy.


