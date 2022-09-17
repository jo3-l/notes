# Significant Figures

Significant figures (s.f. or "sig figs" for short) indicate how precise a measurement is. For physical properties like mass, time, volume, or length, there will always be some margin of error, so a perfectly precise measurement is impossible.

# Counting significant figures

**Rule 1a:** All non-zero digits are significant.

- $123.456$ has 6 s.f.

---

**Rule 1b:** Zeros at the end of a number are insignificant *if no decimal point is shown.*

- $1000$ and $10$ both have 1 s.f.
- $1100$, $120$ and $10.$ have 2 s.f.
- $12500$ has 3 s.f.

---

**Rule 2:** Everything to the right of a decimal point is significant. Note that ideally, a decimal point should not be used without a following digit 

- $1.0$ has 3 s.f.
- $10$ has only 1 s.f.
- $100.0$ has 4 s.f.
- $10.$ has 2 s.f.

---

**Rule 3:** Captive zeros (between two non-zero digits) are significant.

- $403$ and $103$ both have 3 s.f.

---

**Rule 4:** Leading zeros (to the left of a non-zero number) aren't significant (they are only placeholders)

- $25$, $0.025$, and $0.0025$ all have two s.f.

---

**Rule 5:** Trailing zeros are significant and must be justified by the precision of the measuring equipment, if a decimal appears.

---

**Rule 6:** Exact numbers (like SI unit conversion factors) have an infinite number of s.f. and will not limit the precision of a calculation.

For example, the conversion rate $\pu{1 inch} = \pu{2.54 cm}$ has $\infty$ s.f.

# Rounding

When rounding, consider the figure following (i.e., to the right of) the figure that is to be last. The figure you examine is the first figure to be dropped. E.g. when rounding $123$ to 2 s.f. $3$ is the first figure to be dropped.

Now:
- **If the figure is more than 5**, round up. E.g. $3.78721$ to 3 s.f. is $3.79$.
- **If the figure is equal to 5**, round the final number so it's even. E.g. $726.835$ rounded to 5 s.f. is $726.84$, $24.85$ rounded to 3 s.f. is $24.8$, not $24.9$.

# Operations with s.f.

Uncertainty rules override s.f. rules.

**Multiplication, division, n-th roots, exponentiation:** result has as many s.f. as the least number of s.f. in the operands:

- $\underbrace{23}_{\text{2 s.f.}} \times \underbrace{578}_{\text{3 s.f.}} = 13294 \approx \underbrace{1.3 \times 10^4}_{\text{2 s.f.}}$
- $\underbrace{12.3^3}_{\text{3 s.f.}} = 1860.867... \approx \underbrace{1.86 \times 10^3}_{\text{3 s.f.}}$

**Addition, subtraction:** result has as many _decimal places_ as the least number of decimal places in the operands:

- $\underbrace{3.21}_{\text{2 d.p.}} + \underbrace{4.1}_{\text{1 d.p.}} = 7.32 \approx \underbrace{7.3}_{\text{1 d.p.}}$

## Scientific notation

When adding/subtracting numbers in scientific notation, change both numbers to the same exponent first. Then, round the result to the least number of decimal places in the **coefficients** of the operands -- the power of 10 may be ignored. For example:

- $1.23 \times 10^{2} + 4.51 \times 10^{1} = \underbrace{1.23 \times 10^{2}}_{\text{2 d.p.}} + \underbrace{0.451 \times 10^{2}}_{\text{3 d.p.}} \approx \underbrace{1.68 \times 10^2}_{\text{2 d.p.}}$

## Mixed operations

When performing mixed operations with s.f., **round once at the end, never in intermediate calculations.** Doing the latter may lead to incorrect answers. For example, if we have

$$
\begin{align}
&\phantom{{}={}} (\underbrace{2.8}_{\text{2 s.f.}} \times \underbrace{4.532}_{\text{4 s.f.}}) + \underbrace{12.690}_{\text{5 s.f.}} \\
&= \underbrace{12.6896}_{\text{0 d.p.}} + \underbrace{12.690}_{\text{3 d.p.}} && \text{(keep track of precision, but don't round)} \\
&= \underbrace{25.3796}_{\text{0 d.p.}} \\
&= 25. && \text{(round at the end)}
\end{align}
$$

If we rounded on the second step, we would have gotten an incorrect final result of $26$.