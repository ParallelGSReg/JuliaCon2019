# JuliaCon 2019 Proceedings
## GlobalSearchRegression.jl: Building bridges between Machine Learning and Econometrics in Fat-Data scenarios

#### Authors
Panigo Demian (CONICET, UNLP, UNDAV), Pablo, Gluzmann (CONICET, UNLP), Esteban Mocskos (CONICET, UBA), Adan Mauri Ungaro (UNLP), Valentin Ungaro (UNLP) and Nicolás Monzón (UNLP, UNDAV).

### Abstract
The aim of this paper is twofold. The first one is to describe a novel research-project designed for building bridges between machine learning and econometric worlds. The second one is to introduce the main characteristics and comparative performance of the first Julia-native all-subset regression algorithm included in [GlobalSearchRegression.jl (v.1.0.3)](https://github.com/ParallelGSReg/GlobalSearchRegression.jl). As other available alternatives, this algorithm allows researchers to obtain the best model specification among all possible covariate combinations - in terms of user defined information criteria-, but up to 3165 and 197 times faster than STATA and R alternatives, respectively.

#### Credits
The GSReg module, which perform regression analysis, was written primarily by [Demian Panigo](https://github.com/dpanigo/), [Valentín Mari](https://github.com/vmari/) and [Adán Mauri Ungaro](https://github.com/adanmauri/). The GlobalSearchRegression.jl module was inpired by GSReg for Stata, written by Pablo Gluzmann and [Demian Panigo](https://github.com/dpanigo/).
