# MODEL1011080003: iAI549

## Installation

Download this repository, and install with distutils

`python setup.py install`

Or, install using pip

`pip install git+https://github.com/biomodels/MODEL1011080003.git`

To install a specific version (in this example, from the 2014-09-16 BioModels release)

`pip install git+https://github.com/biomodels/MODEL1011080003.git@20140916`

## Usage

Importing the model package.

`import MODEL1011080003 as model`

Get the SBML string from the model

`print model.sbmlString`

If [python-libsbml](https://pypi.python.org/pypi/python-libsbml) bindings are
installed, the libsbml.SBMLDocument object is also accessible

`model.sbml`


# Model Notes


This is metabolic network reconstruction of _Dehalococcoides_ , iAI549,
described in the article  
**Characterizing the metabolism of dehalococcoides with a constraint-based model.**   
Ahsanul Islam M, Edwards EA, Mahadevan R. _PLoS Comput Biol._ 2010 Aug
19;6(8). pii: e1000887. PMID:
[20811585](http://www.ncbi.nlm.nih.gov/pubmed/20811585) , DOI:
[10.1371/journal.pcbi.1000887](http://dx.doi.org/10.1371/journal.pcbi.1000887)

Abstract:  
Dehalococcoides strains respire a wide variety of chloro-organic compounds and
are important for the bioremediation of toxic, persistent, carcinogenic, and
ubiquitous ground water pollutants. In order to better understand metabolism
and optimize their application, we have developed a pan-genome-scale metabolic
network and constraint-based metabolic model of Dehalococcoides. The pan-
genome was constructed from publicly available complete genome sequences of
Dehalococcoides sp. strain CBDB1, strain 195, strain BAV1, and strain VS. We
found that Dehalococcoides pan-genome consisted of 1118 core genes (shared by
all), 457 dispensable genes (shared by some), and 486 unique genes (found in
only one genome). The model included 549 metabolic genes that encoded 356
proteins catalyzing 497 gene-associated model reactions. Of these 497
reactions, 477 were associated with core metabolic genes, 18 with dispensable
genes, and 2 with unique genes. This study, in addition to analyzing the
metabolism of an environmentally important phylogenetic group on a pan-genome
scale, provides valuable insights into Dehalococcoides metabolic limitations,
low growth yields, and energy conservation. The model also provides a
framework to anchor and compare disparate experimental data, as well as to
give insights on the physiological impact of "incomplete" pathways, such as
the TCA-cycle, CO(2) fixation, and cobalamin biosynthesis pathways. The model,
referred to as iAI549, highlights the specialized and highly conserved nature
of Dehalococcoides metabolism, and suggests that evolution of Dehalococcoides
species is driven by the electron acceptor availability.

This model was downloaded from the supplementary materials to the article.

This model originates from BioModels Database: A Database of Annotated
Published Models (http://www.ebi.ac.uk/biomodels/). It is copyright (c)
2005-2011 The BioModels.net Team.  
To the extent possible under law, all copyright and related or neighbouring
rights to this encoded model have been dedicated to the public domain
worldwide. Please refer to [CC0 Public Domain
Dedication](http://creativecommons.org/publicdomain/zero/1.0/) for more
information.

In summary, you are entitled to use this encoded model in absolutely any
manner you deem suitable, verbatim, or with modification, alone or embedded it
in a larger context, redistribute it, commercially or not, in a restricted way
or not..  
  
To cite BioModels Database, please use: [Li C, Donizelli M, Rodriguez N,
Dharuri H, Endler L, Chelliah V, Li L, He E, Henry A, Stefan MI, Snoep JL,
Hucka M, Le Novère N, Laibe C (2010) BioModels Database: An enhanced, curated
and annotated resource for published quantitative kinetic models. BMC Syst
Biol., 4:92.](http://www.ncbi.nlm.nih.gov/pubmed/20587024)


