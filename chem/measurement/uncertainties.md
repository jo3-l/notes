# Uncertainty

Two main types of uncertainty/experimental error:

- **Systematic error:** Biases measurements in the same direction; all too large or too small. E.g., ammeter that displays $\pu{0.1A}$ even if there is no current will lead all measurements being greater by $\pu{0.1A}$.
- **Random error:** Unbiased; revealed when repeated measurements of same quantity show different values. E.g. multiple people use stopwatch to time a race -- all start at slightly different times.

Random errors are the fault of the observer, whereas systematic errors are the fault of both the observer and the instrument.

To avoid random uncertainties one can take multiple measurements and average them out. 

# Reading uncertainties

Reading uncertainties are a type of random uncertainty (e.g. using a ruler to measure an object that lies between two markings on a the ruler.)

The uncertainty in reading an **analogue device** like a ruler is half its smallest width. For example, a ruler with $\pu{0.2cm}$ markings would have an uncertainty of $\pm \pu{0.1cm}$.

The uncertainty in reading a **digital device** like a stopwatch is $\pm 1$ in the least significant digit. E.g. if a stopwatch reads $\pu{15.52s}$ the least significant digit is the $2$ and so the uncertainty is $\pu{0.01s}$.

# Propagation of uncertainties

First, some definitions. For a measurement $a = a_{0}+ \Delta a$, we have:
- absolute uncertainty = $\Delta a$
- fractional uncertainty = $\dfrac{\Delta a}{a_0}$
- percentage uncertainty = $\dfrac{\Delta a}{a_{0}}\times 100\%$

## Addition and subtraction

Absolute uncertainty of the result is sum of absolute uncertainty of operands.

E.g. side length of square is $\pu{(12.4 \pm 0.1)cm}$, then perimeter is $\pu{(49.6 \pm 0.4)cm}$.

## Multiplication and division
Fractional uncertainty of the result is the sum of the fractional uncertainty of the operands.

E.g. if $a = \pu{(2.5 \pm 0.1)cm}$, $b = \pu{(5.0 \pm 0.1)cm}$, then fractional uncertainty of result is

$$
\frac{0.1}{2.5} + \frac{0.1}{5.0} = \frac{3}{50} = 6\%
$$

so the absolute uncertainty is $12.5 \times 6\% = 0.75$. Thus the result is $\pu{(12.5 \pm 0.8)cm^2}$. 

## Powers and roots

Fractional exponent of the result is the fractional uncertainty of the quantity multiplied by the absolute value of the power.

For example, if we have $t = \pu{(2.36 \pm 0.04)s}$ which has fractional uncertainty $\dfrac{0.04}{2.36} \approx 1.695\%$. The fractional uncertainty of the result should thus be $1.695\% \times 2 \approx 3.39\%$.

# Uncertainty and s.f.

Round digits to the uncertainty if provided. E.g. if a value of $\pu{20.01m}$ is given with an uncertainty of $\pm \pu{0.1m}$, the value should be $\pu{20.0m} \pm \pu{0.1m}$.