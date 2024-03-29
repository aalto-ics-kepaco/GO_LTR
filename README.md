# GO_LTR is an LTR Multiview package for Gene Ontology prediction

The detailed description of the **Polynomial Regression via Latent Tensor Reconstruction(LTR)** solver is in *ltr_user_guide_0164_026.pdf* which is located in the docs subdirectory, [LTR user guide](docs/ltr_user_guide_0164_026.pdf)   

## Requirements

The application of the LTR assumes the  **Python** interpreter, version at least **3.7**, and the **Numpy** package, version at least **1.20**. 

To run the examples also
requires the **matplotlib** and **scikit-learn packages**. All these packages
can be freely downloaded and installed from *pypi.org*. 

## Installation

The LTR package might be installed by the following procedures. 

### Directly from the github

>pip3 install git+https://github.com/aalto-ics-kepaco/GO_LTR.git#egg=GO_LTR

### Downloading from github

>mkdir goltrpath

>cd goltrpath

>git clone https://github.com/aalto-ics-kepaco/GO_LTR

After downloading the GO_LTR package it can be installed by the following command: 

>pip3 install ltrpath/GO_LTR


Before installing the LTR package the latest version of the Python packages **pip** and **build** need to be installed. 

>pip3 install --upgrade pip

>pip3 install --upgrade build


The LTR can be imported as

>import GO_LTR as ltr

and the solver object can be constructed by

>cmodel = ltr.ltr_solver_cls(norder=2, rank=10)

Further details about the application of the LTR package can be found within the PDF document in Section \ref{sec:basic_class}, and in Section
\ref{sec:methods_paramaters}, and in the example files, in the
directory of examples.



