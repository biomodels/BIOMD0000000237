# BIOMD0000000237: Schaber2006_Pheromone_Starvation_Crosstalk

## Installation

Download this repository, and install with distutils

`python setup.py install`

Or, install using pip

`pip install git+https://github.com/biomodels/BIOMD0000000237.git`

To install a specific version (in this example, from the 2014-09-16 BioModels release)

`pip install git+https://github.com/biomodels/BIOMD0000000237.git@20140916`

## Usage

Importing the model package.

`import BIOMD0000000237 as model`

Get the SBML string from the model

`print model.sbmlString`

If [python-libsbml](https://pypi.python.org/pypi/python-libsbml) bindings are
installed, the libsbml.SBMLDocument object is also accessible

`model.sbml`


# Model Notes


This a model from the article:  
** A modelling approach to quantify dynamic crosstalk between the pheromone and the starvation pathway in baker's yeast. **   
Schaber J, Kofahl B, Kowald A, Klipp E _FEBS J._2006 Aug; 273(15):3520-33
[16884493](http://www.ncbi.nlm.nih.gov/pubmed/16884493),  
**Abstract:**   
Cells must be able to process multiple information in parallel and, moreover,
they must also be able to combine this information in order to trigger the
appropriate response. This is achieved by wiring signalling pathways such that
they can interact with each other, a phenomenon often called crosstalk. In
this study, we employ mathematical modelling techniques to analyse dynamic
mechanisms and measures of crosstalk. We present a dynamic mathematical model
that compiles current knowledge about the wiring of the pheromone pathway and
the filamentous growth pathway in yeast. We consider the main dynamic features
and the interconnections between the two pathways in order to study dynamic
crosstalk between these two pathways in haploid cells. We introduce two new
measures of dynamic crosstalk, the intrinsic specificity and the extrinsic
specificity. These two measures incorporate the combined signal of several
stimuli being present simultaneously and seem to be more stable than previous
measures. When both pathways are responsive and stimulated, the model predicts
that (a) the filamentous growth pathway amplifies the response of the
pheromone pathway, and (b) the pheromone pathway inhibits the response of
filamentous growth pathway in terms of mitogen activated protein kinase
activity and transcriptional activity, respectively. Among several mechanisms
we identified leakage of activated Ste11 as the most influential source of
crosstalk. Moreover, we propose new experiments and predict their outcomes in
order to test hypotheses about the mechanisms of crosstalk between the two
pathways. Studying signals that are transmitted in parallel gives us new
insights about how pathways and signals interact in a dynamical way, e.g.,
whether they amplify, inhibit, delay or accelerate each other.

This model originates from BioModels Database: A Database of Annotated
Published Models. It is copyright (c) 2005-2009 The BioModels Team.  
For more information see the [terms of
use](http://www.ebi.ac.uk/biomodels/legal.html).  
To cite BioModels Database, please use [Le Novère N., Bornstein B., Broicher
A., Courtot M., Donizelli M., Dharuri H., Li L., Sauro H., Schilstra M.,
Shapiro B., Snoep J.L., Hucka M. (2006) BioModels Database: A Free,
Centralized Database of Curated, Published, Quantitative Kinetic Models of
Biochemical and Cellular Systems Nucleic Acids Res., 34: D689-D691.](http://ww
w.pubmedcentral.nih.gov/articlerender.fcgi?tool=pubmed&pubmedid=16381960)


