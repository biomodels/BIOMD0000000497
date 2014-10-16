# BIOMD0000000497: MODEL1307040000

## Installation

Download this repository, and install with distutils

`python setup.py install`

Or, install using pip

`pip install git+https://github.com/biomodels/BIOMD0000000497.git`

To install a specific version (in this example, from the 2014-09-16 BioModels release)

`pip install git+https://github.com/biomodels/BIOMD0000000497.git@20140916`

## Usage

Importing the model package.

`import BIOMD0000000497 as model`

Get the SBML string from the model

`print model.sbmlString`

If [python-libsbml](https://pypi.python.org/pypi/python-libsbml) bindings are
installed, the libsbml.SBMLDocument object is also accessible

`model.sbml`


# Model Notes


Stanford2013 - Kinetic model of yeast metabolic network (standard)

Large-scale model construction based on a logical layering of data such as
reaction fluxes, metabolite concentrations, and kinetic constants. This model
is built with regulatory information.

This model is described in the article:

[Systematic construction of kinetic models from genome-scale metabolic
networks.](http://identifiers.org/pubmed/24324546)

Stanford NJ, Lubitz T, Smallbone K, Klipp E, Mendes P, Liebermeister W.

PLoS ONE 2013; 8(11): e79195

Abstract:

The quantitative effects of environmental and genetic perturbations on
metabolism can be studied in silico using kinetic models. We present a
strategy for large-scale model construction based on a logical layering of
data such as reaction fluxes, metabolite concentrations, and kinetic
constants. The resulting models contain realistic standard rate laws and
plausible parameters, adhere to the laws of thermodynamics, and reproduce a
predefined steady state. These features have not been simultaneously achieved
by previous workflows. We demonstrate the advantages and limitations of the
workflow by translating the yeast consensus metabolic network into a kinetic
model. Despite crudely selected data, the model shows realistic control
behaviour, a stable dynamic, and realistic response to perturbations in
extracellular glucose concentrations. The paper concludes by outlining how new
data can continuously be fed into the workflow and how iterative model
building can assist in directing experiments.

This model is hosted on [BioModels Database](http://www.ebi.ac.uk/biomodels/)
and identified by:
[BIOMD0000000497](http://identifiers.org/biomodels.db/BIOMD0000000497) .

To cite BioModels Database, please use: [BioModels Database: An enhanced,
curated and annotated resource for published quantitative kinetic
models](http://identifiers.org/pubmed/20587024) .

To the extent possible under law, all copyright and related or neighbouring
rights to this encoded model have been dedicated to the public domain
worldwide. Please refer to [CC0 Public Domain
Dedication](http://creativecommons.org/publicdomain/zero/1.0/) for more
information.


