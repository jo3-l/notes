# Molarity

Molarity (aka molar concentration) is a measure of the amount of solute in a solution:

$$M = \frac{\text{mol of solute}}{\text{L of solution}}.$$

The unit for molarity is $\pu{mol/L}$. A solution with a concentration of $\pu{1 mol/L}$ is said to be $\pu{1 molar}$, or $\pu{1 M}$ for short.

The molarity of a given species $\ce{X}$ is often denoted with square brackets: $\ce{[X]}$.

> [!example]
> $\pu{0.0256g}$ of $\ce{AgNO3}$ is dissolved in $\pu{6.50L}$ of water. Find the resulting $\ce{[AgNO3]}$.

_Solution._ Keeping in mind that molarity is $\pu{mol/L}$, we convert grams to moles and then divide by volume:
$$
\pu{0.0256g} \cdot \frac{\pu{1 mol}}{\pu{169.88g}} \cdot \frac{1}{\ce{6.50L}} = \pu{2.32 \cdot 10^{-5} M}.
$$

# Diluted Solutions

## Simple Dilutions

To solve for the concentration of a simple dilution, use the equation
$$M_1V_{1}= M_2V_2$$
where $M_1$, $V_1$ represent the initial concentration and volume respectively, and $M_2$, $V_2$ represent the final concentration and volume.

> [!example]
> If $\pu{200.0mL}$ of $\pu{0.500 M \ce{NaCl}}$ is added to $\pu{300.0mL}$ of water, what is the resulting $\ce{[NaCl]}$?

_Solution._ We have
$$
\frac{\pu{0.500mol}}{\pu{1L}} \cdot \pu{200.0 \cdot 10^{-3} L} = \pu{500.0\times10^{-3} L} \cdot \ce{[NaCl]}
$$
(Note that the final volume is $\pu{200.0mL} + \pu{300.0mL} = \pu{500.0mL}$.)
Hence, $\ce{[NaCl]} = \pu{0.200 M}$.

## Mixtures of Different Concentrations

To solve for the concentration of a mixture composed of two solutions having different concentrations of the same chemical, either
1. Find the molarity of each solute and add them together.
2. Find the number of moles and divide by the total volume.

> [!tip]
> The first method is usually faster to calculate.

> [!example]
> If $\pu{300.0mL}$ of $\pu{0.250M \ce{NaCl}}$ is added to $\pu{500.0mL}$ of $\pu{0.100 M \ce{NaCl}}$, find the resulting $\ce{[NaCl]}$ of the mixture.

_Solution._ The molarity of the first solute is
$$
\frac{\pu{300.0mL}}{\pu{800.0mL}} \cdot \pu{0.250M} = \pu{0.09375M}
$$
and the molarity of the second is
$$\frac{\pu{500.0mL}}{\pu{800.0mL}} \cdot \pu{0.100M} = \pu{0.0625M}$$
Thus, the resulting $\pu{[NaCl]}$ is simply the sum of the two, $\pu{0.156M}$.

# Concentrations of Ions in Solutions

Given the concentration of a solution, one can calculate the concentration of its constituent ions by multiplying by the mole ratio.

> [!example]
> What is the concentration of $\ce{SO4^2-}$ present in $\pu{0.135 M \ce{Al2(SO4)3}}$?

_Solution._ We have
$$
\frac{\pu{0.135 mol \ce{Al2(SO4)3}}}{\pu{1 L}} \cdot \frac{\pu{3 mol \ce{SO4}}}{\pu{1 mol \ce{Al2(SO4)3}}} = \pu{0.405 M}.
$$

## Mixtures of Different Chemicals

Previously, we discussed [[#Mixtures of Different Concentrations | mixtures of different concentrations of the same chemical]]. Using a similar method, we can find the concentrations of constituent ions in a mixture of different chemicals:
1. Calculate the molarity of each solute.
	1. Then, calculate the molarity of each ion in the solute.
2. Add up the molarities of same ions.

> [!example]
> Find the concentration of all the ions in a mixture of $\pu{100.0mL}$ of $\pu{0.200 M \ce{BaCl2}}$ and $\pu{150.0mL}$ of $\pu{0.400 M \ce{NaCl}}$.

_Solution._ As
$$
\ce{[BaCl2]} = \frac{\pu{100.0mL}}{\pu{250.0mL}} \cdot \pu{0.200M} = \pu{0.0800 M}
$$
the disassociation reaction is
$$\ce{$\underset{\pu{0.0800M}}{\ce{BaCl2}}$ -> $\underset{\pu{0.0800M}}{\ce{Ba^2+}}$ + $\underset{\pu{0.160M}}{\ce{2Cl^-}}$}$$
Likewise, as
$$
\ce{[NaCl]} = \frac{\pu{150.0mL}}{\pu{250.0mL}} \cdot \pu{0.400M} = \pu{0.240M}
$$
the disassociation reaction is
$$\ce{$\underset{\pu{0.240M}}{\ce{NaCl}}$ -> $\underset{\pu{0.240M}}{\ce{Na^+}}$ + $\underset{\pu{0.240M}}{\ce{Cl^-}}$}$$
Putting it together, the mixture is composed of the following ions:
- $\ce{Ba^2+}$ with concentration $\pu{0.0800M}$
- $\pu{Cl^-}$ with concentration $\pu{0.160M}$
- $\ce{Na^+}$ with concentration $\pu{0.240M}$
- $\ce{Cl^-}$ with concentration $\pu{0.240M}$

Since there are two sources of $\ce{Cl^-}$ , we add up the individual concentrations to arrive at our final concentration. There is only one source of $\ce{Ba^2+}$ and $\ce{Na^+}$, so their concentrations remain unchanged.

Thus, our final answer is
- $\ce{[Ba^{+}]} = \pu{0.0800M}$
- $\ce{[Cl^{-]}} = \pu{0.400M}$
- $\ce{[Na^+]} = \pu{0.240 M}$
