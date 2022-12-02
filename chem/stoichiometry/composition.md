# Percent Composition

Percentage of a species (atoms, ion, molecule) in a chemical formula by mass.

To calculate:

1. Calculate molar mass of compound/molecule.
2. Calculate molar mass of species within compound/molecule.
3. Plug into formula:
   $$\text{percent composition} = \frac{\text{molar mass of species}}{\text{molar mass of compound/molecule}} \times 100\%$$

# Types of Formulas

- **Empirical formula (EF):** simplest ratio of different types of atoms in compound. E.g., empirical formula for $\ce{C6H6}$ is $\ce{CH}$.
- **Molecular formula (MF):** actual number of each type of atom in each molecule
- **Structural formula (SF):** shows how the atoms in a molecule are arranged and how atoms are connected

Molecules with same MF but different SF are called isomers.

Ionic compounds have EF, and their SF are lattices.

Covalent compounds have EF, MF, SF. Ethene ($\ce{C2H4}$), propane $\ce{C2H6}$, butene ($\ce{C4H8}$) all have an EF of $\ce{CH2}$ but different MF and EF.

# Empirical Formula

To determine empirical formula:

1. Take the mass of each element.
	- If the mass is not given but percent composition is provided, assume there is $\pu{100g}$ of the substance and work from there. (Any value other than $\pu{100g}$ may also be used, but $100$ is just convenient for calculations.)

2. Determine the number of moles present for each.

4. Divide the resulting molar quantities by the smallest one present.
	- If these quotients are not whole numbers, scale them up so they are.

5. Write the empirical formula using the quotients as coefficients.
	- Make sure elements are written in order from most metallic to least: elements to the left of the periodic table first. If two elements are in the same group, write the one below first.
		- **Exception:** Organic compounds should we written as $\ce{CHO}$, not $\ce{HCO}$.

> [!important]
> When calculating empirical formulas, be sure to **not round intermediate calculations**; keep at least 3 decimal places of precision. Otherwise the final answer may be subtly wrong.

> [!example]
>  $\pu{50.0g}$ of iron reacts with $\pu{22.0g}$ of sulfur. When the reaction is complete, $\ce{11.6g}$ of unreacted iron remained in the crucible with the new compound. What is the EF for this sulfide?

_Solution._ First, note that the mass of the iron consumed in the reaction is $\pu{50.0g} - \pu{11.6g} = \pu{38.4g}$. Now we can calculate the various molar quantities:

$$
\begin{align*}
\pu{38.4g} \cdot \frac{\pu{1 mol \ce{Fe}}}{\pu{55.85g}} &= \pu{0.6876 mol \ce{Fe}}\\
\pu{22.0g} \cdot \frac{\pu{1 mol \ce{S}}}{\pu{32.07g}} &= \pu{0.6860 mol \ce{S}}
\end{align*}
$$

Dividing produces a ratio of approximately $\pu{1 mol \ce{Fe}} : \pu{1 mol \ce{S}}$, so the empirical formula is thus $\ce{FeS}$.

# Molecular Formula

To determine molecular formula, calculate the EF and compare its molar mass to that of the MF. The ratio MF/EF should always be a positive integer.

> [!example]
> A hydrocarbon was found to consist of $\ce{81.8\%}$ carbon and $18.2\%$ hydrogen. Molecular ion measurements in a mass spectrometer show that the hydrocarbon has a molar mass of $\pu{44g/mol}$. What is its molecular formula?
>

_Solution._ First find the EF. Assume that there is $\pu{100g}$ of the substance. Then we have

$$
\begin{align*}
\pu{100g} \cdot 81.8\% \cdot \frac{\pu{1 mol \ce{C}}}{\pu{12.01g}} &= \pu{6.744 mol \ce{C}}\\
\pu{100g} \times 18.2\% \times \frac{\pu{1 mol \ce{H}}}{\pu{1.01g}} &= \pu{18.020 mol \ce{H}}
\end{align*}
$$

Dividing, we have a ratio of $\pu{2.672 mol \ce{H}} : \pu{1 mol \ce{C}}$ which is approximately $\pu{8 mol \ce{H}} : \pu{3 mol \ce{C}}$.

Thus, the EF is $\ce{C3H8}$, which has a molar mass of $\pu{44.11 g mol^-1}$. This is nearly identical to the molar mass of the MF provided in the question, so we conclude that the MF is the same as the EF.
