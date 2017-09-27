---
layout: default
title: Excercises for Metabolic Nomenclature
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

What type of metabolism is this?

#### eats sugar, breathes oxygen

Example: *Paracoccus denitrificans*

<div class="solution">
aerobic chemoorganoheteroph (or aerobic chemotroph for short)
</div>

####
Chlorobi: needs light, eats elemental sulfur and CO2

Paracoccus: eats sugar, breathes nitrate

Desulfovibrio: eats H2 and CO2, breathes sulfate

Anabaena: needs light, eats water and CO2

Methanosaeta: eats H2 and CO2, breathes CO2

Nitromonas: eats ammonia and CO2, breathes oxygen

Rhodobacter: needs light, eats H2 and sugar

Methylococcus: eats methane, breathes oxygen (ambiguous)

A second group of methanogens use methanol (CH
3OH) as a substrate for methanogenesis. These are chemoorganotrophic, but still autotrophic in using CO2 as only carbon source.

Lastly, a third group of methanogens produce both methane and carbon dioxide from acetate (CH
3COO−
) with the acetate being split between the two carbons. These acetate-cleaving organisms are the only chemoorganoheterotrophic
