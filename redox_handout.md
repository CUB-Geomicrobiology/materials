---
title: "Redox & Energetics Cheatsheet"
pdf: "redox_handout.pdf"
layout: default
permalink: /redox_cheatsheet/
header-includes:
- \usepackage{relsize}
- \usepackage{amsmath}
- \usepackage{mhchem}
output:
  pdf_document:
    fig_caption: no
  html_notebook: default
  html_document: default
geometry: margin=0.5in
---

<script type="text/x-mathjax-config">
        MathJax.Hub.Config({TeX: {extensions:["mhchem.js"]}});
</script>


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

## Redox reactions

#### Half reactions

A generalized redox reaction $\ce{a A_{ox} + b B_{red} -> c C_{red} + d D_{ox}}$ can also be written as two **half reactions**.

- $\ce{a A_{ox} + n e^{-} -> c C_{red}}$
- $\ce{b B_{red} -> d D_{ox} + n e^{-}}$

#### Rules for balancing redox reactions

The following is one possible approach for systematically balancing redox reactions.

1. Separate out the two half reactions
2. Balance all elements except $\ce{H}$ & $\ce{O}$
3. Balance $\ce{O}$ with $\ce{H2O}$
4. Balance $\ce{H}$ with $\ce{H+}$
5. Balance charge with $\ce{e-}$ [check yourself here that the number of electrons transferred matches the change in oxidation state]
6. Multiply half reactions so that the number of electrons match
7. Add half reactions together

## Energetics

Consider the generalized redox reaction: 

$$\ce{a*A_{ox} + b*B_{red} -> c*C_{red} + d*D_{ox}}$$

#### Gibbs free energy

The Gibbs free energy of reaction ($\Delta G_R$) quantifies the potential thermodynamic energy of the reaction ($<0\rightarrow$ *exothermic*, $>0\rightarrow$ *endothermic*, $=0\rightarrow$ *at equilibrium*) and can be calculated with:

$$
\Delta G_R = \Delta G_R^0 + RT \ln \frac{\left[\ce{C_{red}}\right]^c\left[\ce{D_{ox}}\right]^d}{\left[\ce{A_{ox}}\right]^a\left[\ce{B_{red}}\right]^b}
= \Delta G_R^0 + RT \ln Q
$$
<div style="visibility: hidden;">
\pagebreak
</div>

The standard Gibbs free energy of the reaction $\Delta G_R^0$ is:

$$\Delta G_R^0 = \left(\sum \Delta G_f \right)_{products}- \left(\sum \Delta G_f \right)_{reactants} = - RT \ln K_{eq}$$

#### Nernst potential

The redox potential ($E$) or electromotrive force is the electron-centric view of a redox reaction (as opposed to the reactant/product centric view inherent in the Gibbs free energy), the two are related as follows:

$$
\begin{aligned}
\Delta G_R &= - n_{e^{-}} \cdot F \cdot E  \\
\Delta G_R^0 &= - n_{e^{-}} \cdot F \cdot E^0 
\end{aligned}
$$

Assuming the reaction is at 25C, plugging in the constants and switching from natural log to base 10 logarithm, this becomes:

$$
E = E^0 - \frac{R T}{n_{e^{-}}  F} \ln Q = E^0 - \frac{59.2\, \ce{mV}}{n_{e^{-}}} \log Q
$$

#### Electron activity

The electron activity $\ce{p}e$ is a theoretical concept similiar to $\ce{p}H$ (the proton activity) that can be calculated from the equilibrium constant ($K_{eq}$) and reaction quotient ($Q$) of a redox couple $\ce{A_{ox} + e^{-} <=> A_{red}}$:

$$
\begin{aligned}
\ce{p}e^0 &= \frac{1}{n_{e^{-}}} \log K \\
\ce{p}e &= \ce{p}e^0 - \frac{1}{n_{e^{-}}} \log Q 
\end{aligned}
$$

$E$ and $\ce{p}e$ are related by $E = \frac{\ln 10 R T}{F} \ce{p}e = 59.2\, \ce{mV} \cdot \ce{p}e$

#### Units

 - Temperature ($T$): in degrees Kelvin ($\ce{K}$) unless otherwise specified
 - Gibbs free energy of reaction ($\Delta G_R$): usually in $\ce{kJ/mol}$ (sometimes $\ce{J/mol}$) where $\ce{mol}$ refers to one of the products or reactants
 - Gibbs free energy of formation ($\Delta G_f$): same units as $\Delta G_R$ ($\ce{kJ/mol}$)
 - Equilibrium constant ($K_{eq}$): dimensionless, technically based on activities instead of concentrations but concentrations are a reasonable approximation in dilute solutions
 - Reaction quotient ($Q$): dimensionless ratio of products over reactions $\left(\prod \left(c_i^{n_i}\right)_{prod} \middle/ \prod \left(c_i^{n_i}\right)_{reac}\right)$, also technically based on activities
 - Nernst potential aka redox potential, electromotive force ($E$): in volts ($\ce{V}$) or milli volts ($\ce{mV}$)
 - Number of electrons ($n_{e^{-}}$): dimensionless (usually an integer number)
 - Electron Activity ($\ce{p}e$): dimensionless
 

#### Constants

 - The ideal gas constant ($\ce{R}$): $8.314\cdot10^{-3} \ce{\frac{kJ}{K \cdot mol}}$
 - The Farady constant ($\ce{F}$): $96.49 \ce{\frac{kJ}{V\cdot mol\, e^{-}}}$

