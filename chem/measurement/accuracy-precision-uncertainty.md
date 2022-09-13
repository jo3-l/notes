# Accuracy vs Precision

**Accuracy:** An accurate measurement is close to the actual value.

**Precise:** A precise measurement is _reproducible_. For the purposes of IB chemistry, more s.f. equates to higher precision.

An instrument may be precise yet inaccurate; this occurs when it hasn't been calibrated properly. (For example, a scale could be incorrectly configured so it starts at $1$ instead of $0$. In this case, all the measurements it yields would be precise and reproducible but be off by $1$ from the actual value.)

Parallax is another phenomenon which may make measurements inaccurate. (Defined as apparent shift in position due to observer's position.)

## Examples

Assume that the actual width of a room is $\pu{5.32000 m}$, and the following measurements are obtained:

1. $\pu{5.45217 m}$: not close to actual value, so not accurate. However, measurement has many s.f. so it's precise.
2. $\pu{5.32001 m}$: close to actual value and has many s.f., so both accurate and precise.
3. $\pu{5.3 m}$: close to actual value but does not have many s.f., so accurate but imprecise.
5. $\pu{7.1 m}$: not close to actual value and does not have many s.f., so neither accurate nor precise.


# Quantifying Accuracy

Accuracy can be quantified as percent deviation from expected value.

$$
\text{percent deviation} = \frac{\text{experimental} - \text{theoretical}}{\text{theoretical}} \times 100
$$

# Quantifying Precision

Precision can be quantified in several ways:

- **Standard deviation:** deviation from the mean, but not used in IB Physics.
  $$
  \text{standard deviation} = \sqrt{\frac{\sum{(x_i - \mu)}}{N}}
  $$
- **Range divided by two:** primary method used in IB Physics.
  $$
  \boxed{\text{range} = \frac{\text{max} - \text{min}}{2}}
  $$
- **Analogue device:** 1/2 of the smallest division is a good guess. Make sure to consider start and end separately. (E.g. a ruler has mm divisions, so the uncertainty would be $\pm \pu{0.5mm}$ at each end, so the total uncertainty = $\pm \pu{1mm}$.)
- **Digital devices:** Uncertainty is equal to $\pm 1$ in the least significant digit.

# Uncertainty Rules

When adding or subtracting measured values, add the absolute uncertainty. For example, if we have a measurement of $\pu{3.2m} \pm \pu{0.1m}$, the absolute uncertainty is just $0.1$.

When multiplying / dividing, add the percent uncertainty. For example, if we have a measurement of $\pu{50.5m} \pm \pu{0.1m}$, the percent uncertainty is $\frac{\pu{0.1m}}{\pu{50.5m}} \approx 0.1\%$.

## Examples

**Addition:**

$$
\begin{align}
(\pu{5.2m} \pm \pu{0.1m}) + (\pu{4.9m} \pm \pu{0.1m}) \\
= (\pu{5.2m + 4.9m})\pm (\pu{0.1m + 0.1m}) \\
= \pu{10.1m} \pm \pu{0.2m}
\end{align}
$$

# Uncertainty and s.f.

Uncertainty may be inferred from s.f. if not given. E.g. given a measurement of $\pu{2.0m}$ the $0$ is inferred to be uncertain and hence the the uncertainty could be $\pm \pu{0.1m}$.

Round digits to the uncertainty if provided. E.g. if a value of $\pu{20.01m}$ is given with an uncertainty of $\pm \pu{0.1m}$, the value should be $\pu{20.0m} \pm \pu{0.1m}$.