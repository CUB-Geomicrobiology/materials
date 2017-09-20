---
layout: default
title: Generating a gene tree from scratch
permalink: /trees_bonus/
---

## Target genes

We are interested in comparing one of the main genes involved in photosynthesis to see if we can figure out where it originated. The name of the gene is **chlL** (for chlorophyll subunit L) in eukaryotes and **bchL** (for bacteriochlorophyll subunit L) in bacteria.

## Finding the protein sequences

- Got the NCBI taxonomy browser https://www.ncbi.nlm.nih.gov/taxonomy
- Enter the name of the organism you would like to include in your analysis (e.g. Nostoc or Cryptomonas)
- Once you found the organism, click on the `Protein` link underneath
- Now the search bar already has your taxonomic ID and you just need to append the gene name afterward (e.g. **chlL**) and search for the protein sequences
- You might get multiple hits, choose the one that seems most reasonable (the name should ideally say something like *Light-independent protochlorophyllide reductase*)
  - Note: if multiple seem to be present, feel free to include them all in your analysis, just make sure you give them different names
- Click on the `FASTA` link underneath
- This is your protein sequence in so-called **FASTA** format (the first line stating with `>` is the name of the sequence, you can adjust that as you see fit)
- Copy the name and whole protein sequence to your clipboard

## Collecting the sequences

- Go to http://www.phylogeny.fr/
- In the menu, click on Phylogeny Analysis -> One click
- Paste your FASTA sequence from above into the box
- Repeat the search for protein sequences for the next organism and append the new sequence also in the Phylogeny Analysis box (do this for ~5-10 sequences, ideally from both eukaryotes and different bacteria)

## Compiling the tree

- As soon as you have all your sequences, click "SUBMIT" and wait until the tree is assembled
- This will take care of alignment and tree building all in one but you can look at the different steps on the different tabs - take a look at the alignment and see if it makes sense to you
- Hint: on the tree tab, you can download the tree in Newick format and upload it into the [iTOL](http://itol.embl.de/) interface which makes for much nicer visualization

## Discussion

What is different about this tree compared to the species tree we built earlier?

For bonus credit: include this tree in your [tree repository](https://classroom.github.com/g/9nWtA6xT).
