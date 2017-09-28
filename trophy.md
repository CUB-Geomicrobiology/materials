---
layout: default
title: Metabolism Exercises
css: solutions.css
permalink: /trophy/
---

<script type="text/x-mathjax-config">
MathJax.Hub.Config({TeX: {extensions:["mhchem.js"]}});
</script>

## Overview

The following schematic is designed to make it easier to figure out what type of metabolism you are looking at. Keep in mind that many organisms are capable of multiple metabolic modes to make a living and many are not mutually exclusive.

{% include image.html file="trophy_overview.png" width="700" caption="Metabolic overview." %}

## Rules

The following rules are a good approach to figuring out metabolism:

1. Identify the energy source: is the organism getting its energy from light or from chemical reactions?
2. Depending on the energy source, figure out how the metabolism relates to $\ce{O2}$
  - If `photo`: is it making $\ce{O2}$ or is it not? (hint, phototrophs can **only** make $\ce{O2} if they get their electrons from water - i.e. are "eating" water)
  - If `chemo`: is it using $\ce{O2}$ as an oxidant / electron acceptor or is it using something else?
3. Identify the carbon source: is the organism getting its carbon from inorganic ($\ce{CO2}$) or from organic materials?
4. Identify the electron source: when the carbon source is inorganic, the electron source is almost always inorganic as well, and likewise for organic sources.
5. Combine all the terms to come up with the final `???-otrophy`

### Special cases
 - if an organism is using both organic AND inorganic carbon and/or electron sources, the metabolism is some kind of `???-mixotrophy`.
 - **fermentation** is always a form of `anaerobic chemoorganoheterotrophy`

### Additional Notes

#### Simplifications

Although the full term (e.g. `aerobic chemoorganoheterotrophy`) is the most accurate way to describe the metabolism, many common metabolic modes often get concatenated in both written and verbal communication. Generally speaking, `photolithoautotrophy` usually drops the redundant `litho` whereas `chemolithoautotrophy` often drops the `auto` instead. `chemoorganoheterotrophy` on the other hand usually just becomes `chemotrophy`, reflecting the fact that the use of organics is by far the most widespread version of `chemotrophy` (e.g. all animals are `chemoorganoheterophs`).

#### **Obligate** vs. **Facultative** and other terms

Because the relationship oxygen is such a fundamental sorting metabolic criterion in today's oxygenated Earth surface environment, there are several additional terms that provide detail on how exactly `chemo-???-trophs` relate to $\ce{O2}$.

- **Facultative anaerobic** `chemo-???-trophs` use oxygen when it is present but can switch to some form of `anaerobic chemo-???-trophy` (including fermentation) if oxygen is absent.
- **Obligate aerobic** `???-trophs` require $\ce{O2}$ replete (**oxic**) growth conditions. **Obligate anaerobic** `???-trophs` _cannot_ grow with $\ce{O2}$ and in fact require $\ce{O2}$ free (**anoxic**) growth conditions.
- Organisms that cannot use $\ce{O2}$ but can tolerate its presence are often called **aerotolerant** `???-trophs`.
- Organisms that can use $\ce{O2}$ only at low concentrations are called **microaerobic** `???-trophs`.

## Exercises

What type of metabolism is this? (Note: "eats" and "breathes" are used in the common sense, not the scientific definition). To see solutions, highlight the hidden text.

#### eats sugar, breathes nitrate

<div class="solution">
anaerobic chemoorganoheterotrophy <br/>
for short: anaerobic chemotrophy or <u>nitrate reduction</b> or <b>denitrification</u> (if $\ce{N2}$ is the end-product)
</div>

Example organism that can do this: [*Paracoccus denitrificans*](https://en.wikipedia.org/wiki/Paracoccus_denitrificans)


#### eats sugar, breathes oxygen

<div class="solution">
aerobic chemoorganoheterophy <br/>
for short: aerobic chemotrophy
</div>

Example organism that can do this: [*Escherichia coli*](https://en.wikipedia.org/wiki/Escherichia_coli), [*Paracoccus denitrificans*](https://en.wikipedia.org/wiki/Paracoccus_denitrificans), many others

#### needs light, eats elemental sulfur and $\ce{CO2}$

<div class="solution">
anoxygenic photolithoautotrophy<br/>
for short: anoxygenic photoautotrophy
</div>

Example organism that can do this: [*Chlorobium*](https://en.wikipedia.org/wiki/Chlorobium) species, for example [*Chlorobium tepidum*](https://en.wikipedia.org/wiki/Chlorobium_tepidum)


#### eats $\ce{H2}$ and $\ce{CO2}$, breathes sulfate

<div class="solution">
anaerobic chemolithoautotrophy<br/>
for short: anaerobic chemolithotrophy or <u>sulfate reduction</u> (organisms that do this are often called sulfate-reducing bacteria or SRBs for short)
</div>

Example organism that can do this: [*Desulfovibrio* species](https://en.wikipedia.org/wiki/Desulfovibrio)


#### eats light, eats water and $\ce{CO2}$

<div class="solution">
oxygenic photolithoautotrophy<br/>
for short: oxygenic phototrophy or just oxygenic photosynthesis (this is what all plants do)
</div>

Example organism that can do this: [*Anaebeana variabilis*](https://en.wikipedia.org/wiki/Anabaena_variabilis)

#### eats $\ce{H2}$ and $\ce{CO2}$, breathes $\ce{CO2}$

<div class="solution">
anaerobic chemolithoautotrophy<br/>
for short: anaerobic chemolithotrophy or more specifically <u>hydrogenotrophic methanogenesis</u> (literally, hydrogen eating methane production since the product of respiring with CO2 is methane)
</div>

Example organism that can do this: [*Methanosaeta* species](https://en.wikipedia.org/wiki/Methanosaeta)

#### eats ammonia and $\ce{CO2}$, breathes $\ce{O2}$

<div class="solution">
aerobic chemolithoautotrophy<br/>
for short: aerobic chemoautotrophy or <u>ammonia oxidation</b> (the first step of <b>nitrification</u>)
</div>

Example organism that can do this: [*Nitromonas* species](https://en.wikipedia.org/wiki/Nitrosomonas)

#### needs light, eats H2 and sugar

<div class="solution">
anoxygenic photomixotrophy
</div>

Example organism that can do this: [*Rhodobacter capsulatus*](https://en.wikipedia.org/wiki/Rhodobacter_capsulatus)

#### eats acetate only

<div class="solution">
anaerobic chemoorganoheterotrophy<br/>
for short: <u>acetoclastic methanogenesis</u> (this is actually methane production by acetate fermentation)
</div>

Example organism that can do this: [*Methanosarcina* species](https://en.wikipedia.org/wiki/Methanosarcina)
