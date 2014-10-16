# BIOMD0000000065: Yildirim2003_Lac_operon

## Installation

Download this repository, and install with distutils

`python setup.py install`

Or, install using pip

`pip install git+https://github.com/biomodels/BIOMD0000000065.git`

To install a specific version (in this example, from the 2014-09-16 BioModels release)

`pip install git+https://github.com/biomodels/BIOMD0000000065.git@20140916`

## Usage

Importing the model package.

`import BIOMD0000000065 as model`

Get the SBML string from the model

`print model.sbmlString`

If [python-libsbml](https://pypi.python.org/pypi/python-libsbml) bindings are
installed, the libsbml.SBMLDocument object is also accessible

`model.sbml`


# Model Notes


This a model from the article:  
**Feedback regulation in the lactose operon: a mathematical modeling study and comparison with experimental data.**   
Yildirim N, Mackey MC _Biophys. J._ 2003
[12719218](http://www.ncbi.nlm.nih.gov/pubmed/12719218) ,  
**Abstract:**   
A mathematical model for the regulation of induction in the lac operon in
Escherichia coli is presented. This model takes into account the dynamics of
the permease facilitating the internalization of external lactose; internal
lactose; beta-galactosidase, which is involved in the conversion of lactose to
allolactose, glucose and galactose; the allolactose interactions with the lac
repressor; and mRNA. The final model consists of five nonlinear differential
delay equations with delays due to the transcription and translation process.
We have paid particular attention to the estimation of the parameters in the
model. We have tested our model against two sets of beta-galactosidase
activity versus time data, as well as a set of data on beta-galactosidase
activity during periodic phosphate feeding. In all three cases we find
excellent agreement between the data and the model predictions. Analytical and
numerical studies also indicate that for physiologically realistic values of
the external lactose and the bacterial growth rate, a regime exists where
there may be bistable steady-state behavior, and that this corresponds to a
cusp bifurcation in the model dynamics.

The model reproduces the time profile of beta-galactosidase activity as shown
in Fig 3 of the paper. The delay functions for transcription (M) and
translation (B and P) have been implemented by introducing intermediates ( I1,
I2 and I3) in the reaction scheme which then give their respective products
(I1-> M, I2 ->B and I3 ->P) after an appropriate length of time. The steady
state values, attained upon simulation of model equations, for Allolactose
(A), mRNA (M), beta-galactosidase (B), Lactose (L), and Permease (P) match
with those predicted by the paper. The model was successfully tested on
Jarnac, MathSBML and COPASI

This model originates from BioModels Database: A Database of Annotated
Published Models (http://www.ebi.ac.uk/biomodels/). It is copyright (c)
2005-2010 The BioModels.net Team.  
For more information see the [terms of
use](http://www.ebi.ac.uk/biomodels/legal.html) .  
To cite BioModels Database, please use: [Li C, Donizelli M, Rodriguez N,
Dharuri H, Endler L, Chelliah V, Li L, He E, Henry A, Stefan MI, Snoep JL,
Hucka M, Le Novère N, Laibe C (2010) BioModels Database: An enhanced, curated
and annotated resource for published quantitative kinetic models. BMC Syst
Biol., 4:92.](http://www.ncbi.nlm.nih.gov/pubmed/20587024)


