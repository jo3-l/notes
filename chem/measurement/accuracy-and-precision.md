# Accuracy vs Precision

**Accuracy:** An accurate measurement is close to the actual value.

**Precision:** A precise measurement is _reproducible_. That is, if a precise measurement is repeated many times, the individual values are close to each other (but not necessarily to the expected value.) **For the purposes of IB chemistry, more s.f. equates to higher precision.**

An instrument may be precise yet inaccurate; this occurs when it hasn't been calibrated properly.

For example, a scale could be incorrectly configured so it starts at $1$ instead of $0$. In this case, all the measurements it yields would be precise and reproducible but be off by $1$ from the actual value.

Parallax -- the apparent shift in position due to the observer's position -- is another phenomenon which may cause measurements to be inaccurate.

## Examples

Assume that the actual width of a room is $\pu{5.32000 m}$, and the following measurements are obtained:

1. $\pu{5.45217 m}$: not close to actual value, so not accurate. However, measurement has many s.f. so it's precise.
2. $\pu{5.32001 m}$: close to actual value and has many s.f., so both accurate and precise.
3. $\pu{5.3 m}$: close to actual value but does not have many s.f., so accurate but imprecise.
5. $\pu{7.1 m}$: not close to actual value and does not have many s.f., so neither accurate nor precise.

# Quantifying Accuracy

Accuracy can be quantified as percent deviation from expected value.

$$
\text{percent deviation} = \frac{\text{experimental} - \text{theoretical}}{\text{theoretical}} \times 100\%
$$

# Quantifying Precision

The precision of a set of values can be quantified using standard deviation, which measures deviation from the mean:

$$
\sigma = \sqrt{\frac{\sum{(x_i - \overline{x})^2}}{N}}
$$

IB Physics does not use standard deviation, and instead estimates uncertainty as half of the difference between the largest and smallest value:

$$
\Delta x = \frac{x_{\text{max}} - x_{\text{min}}}{2}
$$
