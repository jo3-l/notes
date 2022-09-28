# Uncertainty

Typically when one makes a measurement, there is some degree of uncertainty: the true value may be less than or greater than the measurement. Put differently, there is a range of possible values. The most common way to show the range of values is

$$
\text{measurement} = \text{best estimate} \pm \text{uncertainty}
$$

e.g., $\pu{(5.07 \pm 0.02)g}$ means that we got a measurement of $\pu{5.07g}$, but it may be off by $\pu{0.02g}$ in either direction.

## Definition

For a measurement $a = a_{0}+ \Delta a$, we have:
- absolute uncertainty = $\Delta a$
- fractional uncertainty = $\dfrac{\Delta a}{a_0}$
- percentage uncertainty = $\dfrac{\Delta a}{a_{0}}\times 100\%$

Percentage uncertainty and fractional uncertainty are sometimes collectively referred to as **relative uncertainty.**

## Rounding

> [!important] Key Point

 **The absolute uncertainty in the final answer must always be quoted to 1 and only 1 s.f. Round if necessary.** E.g., $\pu{(12.34 \pm 0.12)cm}$ should be rounded to $\pu{(12.3 \pm 0.1)cm}$.
 
**Always round digits to match the uncertainty**; the value and the absolute uncertainty should have the same number of decimal places. E.g. if a value of $\pu{20.01m}$ is given with an absolute uncertainty of $\pm \pu{0.1m}$, the value should be rounded to $\pu{20.0m} \pm \pu{0.1m}$.

# Sources of uncertainty

See [[errors]]. 

# Calculations with uncertainties

## Addition and subtraction

Absolute uncertainty of the result is sum of absolute uncertainty of operands.

E.g. side length of square is $\pu{(12.4 \pm 0.1)cm}$, then perimeter is $\pu{(49.6 \pm 0.4)cm}$.

## Multiplication and division
Fractional uncertainty of the result is the sum of the fractional uncertainty of the operands.

E.g. if $a = \pu{(2.5 \pm 0.1)cm}$, $b = \pu{(5.0 \pm 0.1)cm}$, then fractional uncertainty of $a \times b$ is

$$
\frac{0.1}{2.5} + \frac{0.1}{5.0} = \frac{3}{50} = 6\%
$$

so the absolute uncertainty is $12.5 \times 6\% = 0.75$. As the absolute uncertainty must be quoted to 1 s.f., we round to $0.8$. Thus the final result is $\pu{(12.5 \pm 0.8)cm^2}$. 

## Powers and roots

Fractional exponent of the result is the fractional uncertainty of the quantity multiplied by the absolute value of the power.

For example, suppose we have $t = \pu{(2.36 \pm 0.04)s}$ which has fractional uncertainty $\dfrac{0.04}{2.36} \approx 1.695\%$. The fractional uncertainty of $t^2$ should then be $1.695\% \times 2 \approx 3.39\%$.

## Mixed operations

> [!warning] Common Mistake

When performing a series of operations with uncertainties, **do not round in intermediate calculations; only do so at the end.** Similar reasoning as in [[significant-figures#Mixed operations | mixed operations with s.f.]] applies.
