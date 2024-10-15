---
title       : "Phylogeny 1"
subtitle    : "BNS-2002: Genes, Development, and Evolution"
author      : Dr Axel Barlow
job         : "email: a.barlow@bangor.ac.uk"
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : zenburn      # {zenburn, tomorrow, solarized-dark, ...}
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {selfcontained, standalone, draft}
knit        : slidify::knit2slides
logo        : LA_Full_colour_reversed.svg
biglogo     : A1_FullColour.svg
assets      : {assets: ../../assets}
license     : by-nc-sa

---



<!-- adding bold and italic options -->
<style>
em {
  font-style: italic
}
strong {
  font-weight: bold;
}
</style>

## Lecture schedule

1. Drift and variation (Evolution: Chapter 6)
2. Conservation genetics (Evolution: Chapter 6)
3. **Phylogeny 1 (Evolution: Chapter 16)**
4. Phylogeny 2 (Evolution: Chapter 16)

---

## Sabretooth cats

<img src="./assets/img/smilodon1.png" width="60%" style="display: block; margin: auto 0 auto auto;" />

---

## Sabretooth cats

<img src="./assets/img/sabre_tree.svg" width="85%" style="display: block; margin: auto;" />

--- .segue .dark 

## What is a phylogeny?

--- &twocol

## A representation of the evolutionary process

*** =right

<img src="assets/fig/unnamed-chunk-3-1.png" width="100%" style="display: block; margin: auto;" />

*** =left

- Models how evolution works
- An evolutionary tree
- The tips are species
- Nodes are their common ancestors
- All species descend from a single common ancestor

---

## Key process: Vertical gene transfer

<img src="./assets/img/desc1.svg" width="85%" style="display: block; margin: auto;" />

---

## Key process: Vertical gene transfer

<img src="./assets/img/desc2.svg" width="85%" style="display: block; margin: auto;" />

---

## Key process: Vertical gene transfer

<img src="./assets/img/bears.svg" width="85%" style="display: block; margin: auto;" />

---

## Not a progression

<img src="./assets/img/Human_evolution.svg" width="85%" style="display: block; margin: auto;" />

--- bg:white

<img src="./assets/img/matthew_bonnan.png" width="80%" style="display: block; margin: auto;" />

Credit: Dr. Matthew Bonnan

---

### If humans evolved from monkeys, then why are there still monkeys?

<img src="./assets/img/monkeys.svg" width="90%" style="display: block; margin: auto;" />

--- .segue .dark 

## History

--- &twocol bg:white

*** =left

### Earliest tree. Augustin Augier, 1801

*** =right

<img src="./assets/img/augier.png" width="95%" style="display: block; margin: auto;" />

--- &twocol bg:white

*** =left

### First branching tree of animals. Lamarck, 1809

*** =right

<img src="./assets/img/lamarck.png" width="95%" style="display: block; margin: auto;" />

--- bg:white

### First tree based on fossils. Hitchcock, 1840

<img src="./assets/img/hitchcock.png" width="70%" style="display: block; margin: auto;" />

--- &twocol bg:white

*** =left

### First evolutionary tree (non-creationist). Darwin, 1837

*** =right

<img src="./assets/img/darwin.png" width="80%" style="display: block; margin: auto;" />

--- bg:white

### Refined for “On the Origin of Species”, Darwin, 1859

<img src="./assets/img/darwin2.png" width="70%" style="display: block; margin: auto;" />

--- &twocol bg:white

*** =left

### Position of humans in the tree. Haeckel, 1879

*** =right

<img src="./assets/img/haekel.png" width="80%" style="display: block; margin: auto;" />

--- bg:white

<iframe src = 'https://www.onezoom.org/life/@biota=93302?otthome=%40%3D44565#x400,y581,w0.7630'></iframe>

--- .segue .dark 

## Phylogenetics: the study of phylogenies

---

## Phylogenetics 

- An entire field of evolutionary biology!
- Combines knowledge from multiple areas: 
- evolutionary biology
- genetics
- mathematics
- computer science
- Multiple specific journals

--- &twocol

## Data: Morphology

*** =left

- suitable for fossil and living species
- generally based on **shared derived** characteristics 
- ancestral states identified using **outgroup**
- optimal tree selected based on **parsimony**
- limited numbers of characters may be available
- generally no model of evolution
- **Homoplasy** is independent evolution of similar states
  - convergent evolution
  - parallel evolution
  - reversal

*** =right

<img src="./assets/img/gfreern.svg" width="50%" style="display: block; margin: auto 0 auto auto;" />

--- bg:white

## Data: Morphology

<img src="./assets/img/morph.svg" width="90%" style="display: block; margin: auto;" />

--- &twocol

## Data: genetics

*** =left

- DNA, RNA or amino acid sequences
- Many characters
- Simple model of substitution
- many analytical methods
- Molecular clock
- evolution can be complex
- Difficult to apply to fossils (ancient DNA)
- Homoplasy still exists
- saturation by repeated substitutions

*** =right

<img src="./assets/img/dna-1889085.jpg" width="100%" style="display: block; margin: auto 0 auto auto;" />

--- &twocol

## Gene tree (single locus tree)

*** =left

- Evolutionary history of a single locus
- (not always an actual gene)
- Any recombining genome has multiple loci, each with its own gene tree
- Easy to calculate using genetic data (often sequences)
- Historical reliance on mitochondrial DNA
- Gene trees may differ
  - **incomplete lineage sorting**
  - **admixture**
  
**More in next lecture**

*** =right

<img src="./assets/img/Gene_Loci_and_Alleles.png" width="75%" style="display: block; margin: auto 0 auto auto;" />

---

## Terminology

<img src="./assets/img/term.png" width="90%" style="display: block; margin: auto;" />

--- &twocol

## Clades

*** =left

- A clade contains one ancestor and all its descendents
- It is a monophyletic group
- Modern taxonomy (generally) tries to align with clades
- Not case for all:
  - lizards
  - reptiles
  - elapids
  - toads
  - birds of prey

*** =right

<img src="./assets/img/squam.jpg" width="100%" style="display: block; margin: auto;" />

--- .segue .dark 

## Using phylogenies

--- &twocol

## Placing enigmatic taxa in the tree

*** =left

- Understand relationships of problematic taxa
- Genetic methods especially useful
- Molecular dating 
- Recent trend for extinct species

*** =right

<img src="./assets/img/praekudarensis.png" width="100%" style="display: block; margin: auto;" />

--- &twocol

## Understanding evolution of novel traits

*** =left

**Giant beaver (*Castoroides*)**

- 2 m long, up to 125 kg, 15 cm incisors
- Extinct ~12 Ka, coinciding with arrival of Clovis people
- Several derived adapatations for wood cutting and aquatic life
- Information on evolution of "ecosystem engineers"?

*** =right

<img src="./assets/img/castoroides-size.jpg" width="85%" style="display: block; margin: auto;" />

<img src="./assets/img/Giant-beaver-fieldmuseum.jpg" width="85%" style="display: block; margin: auto;" />

---

## Giant beaver mitogenome phylogeny

<img src="./assets/img/castor_tree.svg" width="80%" style="display: block; margin: auto;" />

---

## Giant beaver mitogenome phylogeny

<embed src="./assets/img/Xenikoudakis et al. - 2020 - Ancient DNA reveals twenty million years of aquatic life in beavers.pdf" width="100%" height="500" type="application/pdf" />

--- &twocol

## Measuring trait evolution

*** =left

**Mediterranean Dwarf elephants**

- Multiple Mediterranean islands
- 1.5 to 2.3 m at shoulder
- Direct ancestor is *Palaeoloxodon antiquus*
- Example of insular dwarfism
- Phylogeny could provide information on the dwarfing rate


*** =right

<img src="./assets/img/Elephas mnaidriensis Grotta Puntali di notte.jpg" width="60%" style="display: block; margin: auto;" />

<img src="./assets/img/Palaeoloxodon_falconeri_Size_Comparison.svg.png" width="100%" style="display: block; margin: auto;" />

---

## Dwarfing rate

<img src="./assets/img/dwarf.svg" width="100%" style="display: block; margin: auto;" />

---

## Dwarfing rate

<embed src="./assets/img/Baleka et al. - 2021 - Estimating the dwarfing rate of an extinct Sicilian elephant.pdf" width="100%" height="500" type="application/pdf" />

--- &twocol

## Comparative phylogenetic method

*** =left

- species share an evolutionary history
- a trait in many species may result from a single evolutionary shift
- traits may evolve in a distant ancestor
- need to locate evolutionary shifts on the phylogeny

*** =right

<img src="./assets/img/bird_bird_fish.svg" width="100%" height="500" />

---

## Venom evolution in saw-scaled vipers

<img src="./assets/img/echis.svg" width="100%" height="500" />

--- &twocol

## Species discovery and delimitation

*** =left

- Divergent clades and lineages may be separate species
- Needs me backed up with additional evidence
  - Morphology
  - Behaviour
  - Multiple loci??
  - etc...

### Example: Zimbabwe rinkhals

*** =right

<img src="./assets/img/hema.svg" width="100%" height="500" />

--- bg:white

## Zimbabwe rinkhals

<img src="./assets/img/hema2.svg" width="110%" height="500" style="display: block; margin: auto;" />

---

## Zimbabwe rinkhals

<embed src="./assets/img/Major et al. - 2023 - Museum DNA reveals a new, potentially extinct species of rinkhals (Serpentes Elapidae Hemachatus).pdf" width="100%" height="500" type="application/pdf" />

--- &thankyou

## Next time:

**More phylogeny...**

