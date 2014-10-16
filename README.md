# MODEL8687196544: Niederer2006_CardiacMyocyteRelaxation

## Installation

Download this repository, and install with distutils

`python setup.py install`

Or, install using pip

`pip install git+https://github.com/biomodels/MODEL8687196544.git`

To install a specific version (in this example, from the 2014-09-16 BioModels release)

`pip install git+https://github.com/biomodels/MODEL8687196544.git@20140916`

## Usage

Importing the model package.

`import MODEL8687196544 as model`

Get the SBML string from the model

`print model.sbmlString`

If [python-libsbml](https://pypi.python.org/pypi/python-libsbml) bindings are
installed, the libsbml.SBMLDocument object is also accessible

`model.sbml`


# Model Notes


This a model from the article:  
**A quantitative analysis of cardiac myocyte relaxation: a simulation study.**   
Niederer SA, Hunter PJ, Smith NP. _Biophys J._ 2006:90(5):1697-722.
[16339881](http://www.ncbi.nlm.nih.gov/pubmed/16339881) ,  
**Abstract:**   
The determinants of relaxation in cardiac muscle are poorly understood, yet
compromised relaxation accompanies various pathologies and impaired pump
function. In this study, we develop a model of active contraction to elucidate
the relative importance of the [Ca2+]i transient magnitude, the unbinding of
Ca2+ from troponin C (TnC), and the length-dependence of tension and Ca2+
sensitivity on relaxation. Using the framework proposed by one of our
researchers, we extensively reviewed experimental literature, to
quantitatively characterize the binding of Ca2+ to TnC, the kinetics of
tropomyosin, the availability of binding sites, and the kinetics of
crossbridge binding after perturbations in sarcomere length. Model parameters
were determined from multiple experimental results and modalities (skinned and
intact preparations) and model results were validated against data from length
step, caged Ca2+, isometric twitches, and the half-time to relaxation with
increasing sarcomere length experiments. A factorial analysis found that the
[Ca2+]i transient and the unbinding of Ca2+ from TnC were the primary
determinants of relaxation, with a fivefold greater effect than that of
length-dependent maximum tension and twice the effect of tension-dependent
binding of Ca2+ to TnC and length-dependent Ca2+ sensitivity. The affects of
the [Ca2+]i transient and the unbinding rate of Ca2+ from TnC were tightly
coupled with the effect of increasing either factor, depending on the
reference [Ca2+]i transient and unbinding rate.

This model was taken from the [CellML
repository](http://www.cellml.org/models) and automatically converted to SBML.  
The original model was: [ **Niederer, Hunter, Smith. (2006) - version02**
](http://www.cellml.org/models/niederer_hunter_smith_2006_version02)  
The original CellML model was created by:  
**Terkildsen, Jonna,**   
j.terkildsen@auckland.ac.nz  
The University of Auckland  
Auckland Bioengineering Institute  

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


