*********************************************************
Package PFIM v5.0 beta

Description, Installation, Content 
*********************************************************

*********************************************************
Description 
*********************************************************

Package: PackagePFIM 

Type: Package

Title: Population Fisher Information Matrix

Version: 5.0 beta version

Date: 2020-18-06

Author: 
    France Mentré, <france.mentre@inserm.fr>,
    Hervé Le Nagard, <herve.lenagard@inserm.fr>,
    Romain Leroux, <romain.leroux@inserm.fr>,
    Jérémy Seurat, <jeremy.seurat@inserm.fr>,
    on the behalf of the PFIM group 
    IAME, INSERM, UMR1137, University Paris Diderot, Paris, France.

Maintainer: 
    Hervé Le Nagard <herve.lenagard@inserm.fr>
    Romain Leroux <romain.leroux@inserm.fr>
    Jérémy Seurat <jeremy.seurat@inserm.fr>

Description: Evaluate or optimize the Fisher Information Matrix 
             for a population pharmacokinetic/pharmacodynamic model.
             
Depends: 
    R (>= 4.0.0)

License: GPL (>=2)

Suggests: testhat, knitr

The package PFIM5.0 use the following packages:
    methods,
    pracma,
    utils,
    scales,
    ggplot2,
    gridExtra,
    testthat,
    Deriv,
    Matrix,
    nlme,
    Rcpp,
    RcppArmadillo,
    inline,
    markdown,
    rmarkdown,
    knitr,
    qpdf,
    stats
    Rcpp,
    RcppArmadillo
    
The documentation is generated with RoxygenNote: 7.1.1

*********************************************************
Installation 
*********************************************************

1. Download the file  PFIM_v5.0_beta-main.zip
2. Install the package PFIM 5.0 beta from the archive ackagePFIM_5.0.tar
3. The folder for working wihth PFIM 5.0 beta is PackagePFIM 

The paths is : PFIM_v5.0_beta-main\PFIM_v5.0_beta-main\PackagePFIM_5.0.tar\PackagePFIM_5.0\PackagePFIM

4. When you generate a markdown report for a PFIM project it is saved in the folder PackagePFIM\inst\rmarkdown\templates\pfim_report\skeleton

*********************************************************
Content 
*********************************************************

The folder PackagePFIM contains the files for the beta version of the package PFIM5.0 :

1. DESCRIPTION and NAMESPACE : for package description and compilation
2. DocumentationDev_PFIM5.0.pdf : the documentation of all the classes, methods and functions
3. tests, a folder that contains many tests for the :
- evaluation of PK, PKPD and PKPKPD models : analytic, ode and ode with infusion
- optimisation for PK models analytic and ode & PKPD models with the : simplex, multiplicative, Fedorov-Wynn, PGBO and PSO algorithms 
4. R : R S4 classes 
5. inst and man : for documentation and the pdf report of a PFIM project


