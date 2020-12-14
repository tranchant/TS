# MANIPULATION OF NGS DATA FOR GENOMIC AND POPULATION GENETICS ANALYSES

```{figure} https://www.transmittingscience.com/wp-content/uploads/2019/09/Manipulation-of-NGS-Data-for-Genomic-and-Population-Genetics-Analyses-300x300.jpg
---
height: 150px
name: my-image
---
```

# Environment

* Linux 
* Bioinformatics tool 
* [vm](https://biosphere.france-bioinformatique.fr)
* slack : link

# Monday "Discovering the linux world throught jupyter world"

## Discover the NGS world ! __link__

```{figure}  https://lh3.googleusercontent.com/proxy/1rPwglBhZPOjyZDv_HOvsDuZBBlHTXOj064R8O06vycCmluJzzlkSoEfiD2KPZBDuKeKQYk2XBnA02BrG0mKuqOe1qeyfaMgihpNTwk
---
height: 150px
name: my-image
---
```

## Practice !
* ls cd pwd cat wc -l grep pipe
* introduire exemple exo applicatifs

## Deeply

* exercices compter nb reads / fastq stat

* plot jupyter stat ?

* quelles analyses ? gff - bedtools intersect localisation capture

* Exercice qui tue/Bonus !!!! pipe


# Tuesday "Mapping and call variant calling"

## Discover SNP calling methodology

## Practice !

* mapping un individu GATK4 * bwa aln/sampe / picardtools / appel SNP

* xplciation TP Pipeline à faire pour les 15 individus (boucle / 1 par 1)

* Gestionnaire WF Nextflow WF CRG ? presentation 10 min -> TOGGLE

## Deeply

* TP Pipeline (canveas : boucle, TOGGLe)

* 15 vcfs, puis 1 vcf final


# Wednesday 

* Visualisation bam indiv 13/14 TABLET

* SNP filtering

* snmf

## Deeply

* Canveas : ACP code R

* plot variant snp (densité filtré / non filtré)



# Thursday Jour4

1h30 -> pause

30-45 minutes : debrief veille

Presentation Longread methodo + applications SV

PAUSE

Jupyter book bash

nanoplot

mapping reads ONT vs Genome ref avec minimap2 et un individu

Après midi

Sniffle (documentation par eux meme)

vcf sniffle / vcf SNP

plotter carte densité SNP / SV

Jour5

1h30 -> pause

30-45 minutes : debrief veille

principe Assemblage Short read / Longread Nucmer

pause

assemblage short read (abyss) / long read (raven)

Dgenies

Applications : synthese techno short et long reads (pdf)

Après midi

15 assembkages et comparaison (short/long read) -> essayer comprendre ce qui s ets passé pour l organisme

synthèse 16h ?

We can estimate the mass of Jupiter from the period and size of an object orbiting it. For example, we can use Jupiter's moon Callisto to estimate it's mass.

Callisto's period: $p_{c}=16.7 days$

Callisto's orbit radius: $r_{c}=1,900,000 km$

Now, using [Kepler's Law](https://solarsystem.nasa.gov/resources/310/orbits-and-keplers-laws/) we can work out the mass of Jupiter.

```{math}
:label: eq1
m_{j} \approx \frac{r_{c}}{p_{c}} \times 7.9 \times 10^{10}
```

```{math}
:label: eq2
m_{j} \approx 1.9 \times 10^{27} kg
```


```{margin} Did you know?
Jupiter is 11.0x larger than Earth!
```

## Linux

```{note}
I am a useful note!
```

```{tip}
I am a useful note!
```

```{warning}
I am a useful note!
```

```{hint}
NASA provides a lot more information about the physical characteristics of Jupiter [here](https://solarsystem.nasa.gov/planets/jupiter/by-the-numbers/).
```


There might even be more planets out there with a similar mass to Jupiter {cite}`mayor1995jupiter`!

## Bibliography

```{bibliography} references.bib
```