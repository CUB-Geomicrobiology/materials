---
layout: default
title: Redox Refresher
permalink: /redox/
---

## Terminology

 - **Oxidation state**: a number that represents the number of electrons that an atom has gained or lost
 - **Reduction**: gain electrons (↓ oxidation state)
 - **Oxidation**: lose electrons (↑ oxidation state)


|                       General Equation                        |                        Example                         |
|:-------------------------------------------------------------:|:------------------------------------------------------:|
| $\ce{A_{red} <=>T[oxidation][reduction] A_{ox}}$ | $\ce{CH4 <=>T[oxidation][reduction] CO2}$ |

 - **Oxidant**: chemical species that oxidizes something else, and gets reduced
 - **Reductant**: chemical species that reduces something else, and gets oxidized
 - **Redox potential**: the thermodynamic preference of a species to be an oxidant or a reductant, measured in volts (typically V or mV)

## Oxidation state

The following rules allow you to work out the oxidation states for elements with complex oxidation states.

1. Any atoms in elemental form have an oxidation state of 0 ex: $\ce{O2}$, $\ce{N2}$, $\ce{S0}$, $\ce{Fe(s)}$
2. The more electronegative elements in a compound will have a negative oxidation state, while the less electronegative elements in a compound will have a positive oxidation state. As a result of their electronegativities, some elements will almost always have certain oxidation states.
   - Alkali metals are always +1
   - Alkaline earth metals are always +2
   - Fluorine is always -1
   - Hydrogen is almost always +1 (**Exception**: metal hydrides, ex: $\ce{NaH}$, where H is -1 because Na is +1 and the compound is neutral.)
   - Oxygen is almost always -2 (**Exceptions**: peroxides, ex $\ce{H2O2}$, where O is -1 because H can only donate 1 electron and the compound is neutral; and $\ce{F2O}$, where O is +2 because F is the only thing more electronegative than O.
3. The sum of oxidation states in a species is equal to the net charge of the species.

Carbon has 4 valance electrons, so it can lose up to 4 electrons or gain up to 4 electrons for a full outer shell. Therefore, carbon has 9 possible oxidation states, from -4 to +4.

| Oxidation state |     -4     |     -3      |     -2      |     -1      |      0      |      +1       |     +2      |     +3      |     +4     |
|-----------------|:----------:|:-----------:|:-----------:|:-----------:|:-----------:|:-------------:|:-----------:|:-----------:|:----------:|
| Example         | $\ce{CH4}$ | $\ce{C2H6}$ | $\ce{C2H4}$ | $\ce{C2H2}$ | $\ce{CH2O}$ | $\ce{C2H2O2}$ | $\ce{CHO2-}$ | $\ce{C2O4-}$ | $\ce{CO2}$ |


### Practice problems

Assign oxidation states to each atom in these compounds

|             |                                **Acetate**                                 |                                **Succinate**                                 |                                **Fumarate**                                 |                                **Ethanol**                                 |
|-------------|:--------------------------------------------------------------------------:|:----------------------------------------------------------------------------:|:---------------------------------------------------------------------------:|:--------------------------------------------------------------------------:|
| Structure   | ![]({{ site.baseurl }}/assets/redox_acetate.png){:class="img-height-90px"} | ![]({{ site.baseurl }}/assets/redox_succinate.png){:class="img-height-90px"} | ![]({{ site.baseurl }}/assets/redox_fumarate.png){:class="img-height-90px"} | ![]({{ site.baseurl }}/assets/redox_ethanol.png){:class="img-height-50px"} |
| Net charge  |                                                                            |                                                                              |                                                                             |                                                                            |
| Hydrogen(s) |                                                                            |                                                                              |                                                                             |                                                                            |
| Oxygen(s)   |                                                                            |                                                                              |                                                                             |                                                                            |
| Carbon(s)   |                                                                            |                                                                              |                                                                             |                                                                            |

### [Solutions]({{ site.baseurl }}/redox_solutions/)

Only click this link to check the solutions for the above practice problems.

## Redox reactions

#### Half reactions

Any redox reaction $\ce{A_{red} + B_{ox} -> B_{red} + A_{ox}}$ can also be written as two **half reactions**.

- $\ce{A_{red} -> A_{ox} + e-}$
- $\ce{B_{ox} + e- -> B_{red}}$

Half reactions are a useful concept for thinking about redox. However, remember that they are a theoretical construct as there are not really any free electrons in a chemical system. A full chemical equation describing a metabolic reaction or pathway should always have its $\ce{e-}$ cancelled out by combining the involved half reactions.

#### Rules for balancing redox reactions

The following is one possible approach for systematically balancing redox reactions.

1. Separate out the two half reactions
2. Balance all elements except $\ce{H}$ & $\ce{O}$
3. Balance $\ce{O}$ with $\ce{H2O}$
4. Balance $\ce{H}$ with $\ce{H+}$
5. Balance charge with $\ce{e-}$ [check yourself here that the number of electrons transferred matches the change in oxidation state]
6. Multiply half reactions so that the number of electrons match
7. Add half reactions together

### Practice Problems

Write balanced redox reactions for each of these metabolisms.

#### Example: Glucose respiration coupled to nitrate reduction

Pseudo reaction (not balanced): $\ce{C6H12O6 + NO3- -> CO2 + N2}$

- Step 1: separating half reactions. $\ce{C6H12O6 -> CO2}$ and $NO3- -> N2$
- Steps 2-5: balancing the half reactions.
  - $\ce{C6H12O6 + 6 H2O -> 6 CO2 + 24 H+ + 24 e-}$ (The oxidation state of C is 0 in glucose and +4 in $\ce{CO2}$ - since there are 6 carbons, that requires 24 electrons)
  - $\ce{2 NO3- + 12 H+ -> N2 + 6 H2O}$ (The oxidation state of N is +5 in nitrate and O in $\ce{N2}$ - since there are 2 nitrogens, that requires 10 electrons)
- Step 6: matching the half reactions.
  - $\left[\ce{C6H12O6 + 6 H2O -> 6 CO2 + 24 H+ + 24 e-}\right] \cdot 5 = \ce{120 e-}$
  - $\left[\ce{2 NO3- + 12 H+ -> N2 + 6 H2O}\right] \cdot 12 = \ce{120 e-}$
- Step 7: combining the half reactions.
  - $\ce{5 C6H12O6 + 30 H2O + 24NO3- + 144H+ + 120 e- -> 30 CO2 + 120 H+ + 120 e- + 12 N2 + 72 H2O}$
  - which can be simplified to $\ce{5 C6H12O6 + 24 NO3- + 24 H+ -> 30 CO2 + 12 N2 + 42 H2O}$

#### Iron oxidation coupled to nitrate reduction

Pseudo reaction (not balanced): $\ce{Fe^{2+} + NO3- -> Fe(OH)3 + N2}$

#### Iron-oxidizing anoxygenic phototrophy

Pseudo reaction (not balanced): $\ce{HCO3- + Fe^{2+} -> CH2O + Fe(OH)3}$

#### Methane oxidation coupled to sulfate reduction

Pseudo reaction (not balanced): $\ce{CH4 + SO4^{2-} -> CO2 + HS-}$

#### Ammonia oxidation coupled to iron reduction

Pseudo reaction (not balanced): $\ce{NH4+ + FeOOH -> NO2- + Fe^{2+}}$

### [Solutions]({{ site.baseurl }}/redox_solutions/)

Only click this link to check the solutions for the above practice problems.
