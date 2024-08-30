---
title: 'BioHackEU23 report: Template for the very long title'
title_short: 'BioHackEU23 #26: unknown chemical substances'
tags:
  - cheminformatics
  - PubChem
  - unknown chemical substances
authors:
  - name: Yosuke Kawai
    affiliation: 1
  - name: Toshiaki Katayama
    affiliation: 2
  - name: Maxat Kulmanov
    affiliation: 3
  - name: Toyoyuki 
    affiliation: 4
  - name: Yuki
    affiliation: 5
  - name: Nobutaka
    affiliation: 6
  - name: Hirokazu
    affiliation: 7
  - name: Tsuyoshi
    affiliation: 8
  - name: Dorothy Ellis
    affiliation: 9
  - name: Pitiporn (Sam)
    affiliation: 10
  - name: Mayumi
    affiliation: 11
  - name: Núria
    affiliation: 12
  - name: Shuichi
    affiliation: 13
  - name: Kentaro (Yamaken)
    affiliation: 14
  - name: David
    affiliation: 15
  - name: Takatomo
    affiliation: 16
  - name: Hiroyuki Mishima
    affiliation: 17
  - name: Tazro
    affiliation: 18
affiliations:
  - name: First Affiliation
    index: 1
  - name: Second Affiliation
    index: 2
  - name: RIKEN Center for Integrative Medical Sciences
    index: 9
date: 30 August 2024
cito-bibliography: paper.bib
event: BH23EU
biohackathon_name: "BioHackathon Japan 2024"
biohackathon_url:   "https://biohackathon-europe.org/"
biohackathon_location: "Fukushima, Japan, 2024"
group: Genome variation
# URL to project git repo --- should contain the actual paper.md:
git_url: https://github.com/biohackrxiv/bh24-genome-variation
# This is the short authors description that is used at the
# bottom of the generated paper (typically the first two authors):
authors_short: First Author \emph{et al.}
---


# Introduction

The widespread use of sequencers has generated a flood of data that has greatly faciliated the analysis and understanding of the human genome. Simple variations such as single nucleotide variants (SNVs) and indels have been integrated with the comprehensive Japanese genetic variation database TogoVar, but there is currently no standardized representation for structural variants. Pangenome graphs have also emerged as a powerful tool to integrate multiple haplotypes. To facilitate the integration of structural variants, we developed a Common Workflow Language (CWL) script to add TogoVar information to variant call format (VCF) files. We also ....

# Formatting

This document use Markdown and you can look at [this tutorial](https://www.markdowntutorial.com/).

## Subsection level 2

Please keep sections to a maximum of only two levels.

## Tables and figures

Tables can be added in the following way, though alternatives are possible:

Table: Note that table caption is automatically numbered and should be
given before the table itself.

| Header 1 | Header 2 |
| -------- | -------- |
| item 1 | item 2 |
| item 3 | item 4 |

A figure is added with:

![Caption for BioHackrXiv logo figure](./biohackrxiv.png)

# Other main section on your manuscript level 1

Lists can be added with:

1. Item 1
2. Item 2

# Citation Typing Ontology annotation

You can use [CiTO](http://purl.org/spar/cito/2018-02-12) annotations, as explained in [this BioHackathon Europe 2021 write up](https://raw.githubusercontent.com/biohackrxiv/bhxiv-metadata/main/doc/elixir_biohackathon2021/paper.md) and [this CiTO Pilot](https://www.biomedcentral.com/collections/cito).
Using this template, you can cite an article and indicate _why_ you cite that article, for instance DisGeNET-RDF [@citesAsAuthority:Queralt2016].

The syntax in Markdown is as follows: a single intention annotation looks like
`[@usesMethodIn:Krewinkel2017]`; two or more intentions are separated
with colons, like `[@extends:discusses:Nielsen2017Scholia]`. When you cite two
different articles, you use this syntax: `[@citesAsDataSource:Ammar2022ETL; @citesAsDataSource:Arend2022BioHackEU22]`.

Possible CiTO typing annotation include:

* citesAsDataSource: when you point the reader to a source of data which may explain a claim
* usesDataFrom: when you reuse somehow (and elaborate on) the data in the cited entity
* usesMethodIn
* citesAsAuthority
* citesAsEvidence
* citesAsPotentialSolution
* citesAsRecommendedReading
* citesAsRelated
* citesAsSourceDocument
* citesForInformation
* confirms
* documents
* providesDataFor
* obtainsSupportFrom
* discusses
* extends
* agreesWith
* disagreesWith
* updates
* citation: generic citation


# Results


# Discussion

...

## Acknowledgements

...

## References
