The Quantitative Biomedical Inference group (QuBIc) at the University of Oxford
applies inference (estimation) techniques from information engineering to biomedical data, 
primarily with a view to clinical application.

## Projects and Documentation

### Fabber

Fabber is a Bayesian model fitting framework which uses the Variational Bayes
algorithm to do fast model fitting of nonlinear forward models.

 - [Fabber core](https://fabber-core.readthedocs.io) defines the main model fitting algorithm
   and contains a few simple generic models for testing and demonstration purposes.
 - [Fabber DCE models](https://fabber-dce.readthedocs.io) is a set of Fabber models for
   DCE-MRI data
 - [pyfab](https://pyfab.readthedocs.io) is a Python API for Fabber
 
### Quantiphyse

Quantiphyse is a GUI viewing and analysis package for biomedical imaging data. 
As well as generic visualisation and processing functionality, it contains a set of
plugins for processing specific kinds of imaging data including ASL, DCE, CEST, DSC
and quantitative BOLD.

- [Quantiphyse](https://quantiphyse.readthedocs.io) is the main application. Other
  repositories contain various plugins however documentation for these is kept
  centrally.
  
### ASL processing pipelines

These are FSL-based pipelines for processing ASL data

 - [oxford_asl / basil](https://asl-docs.readthedocs.io/) is the standard FSL
   based pipeline for processing ASL data
 - [OXASL](https://oxasl.readthedocs.io/en/latest/) is a new Python-based
   pipeline, largely compatible with `oxford_asl` but with some new features
   and also supporting multiphase and vessel-encoded ASL data
   
 
