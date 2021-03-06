*Statistics, Finance,....*

* [ACTUARIAL SCIENCE](#actuarial-science)
   * [Econometrics](#econometrics) 
* [BENCHMARKS](#benchmarks)
   * [Optimization](#optimization)
   * [Preprocessor](#preprocessor)    
* [OPERATIONS RESEARCH](#operations-research)
* [STATISTICS](#statistics)
   * [Statistical Tests](#stat-tests)
   * [Valuation](#valuation)
* [VIDEOS](#videos)


# ACTUARIAL SCIENCE 
### Econometrics 
* copula.jl :: [Julia Copula package implements the gaussian AR1 copula](https://github.com/floswald/copula.jl)
* DynamicFactorModels.jl :: [Dynamic Factor Models for Julia](https://github.com/joidegn/DynamicFactorModels.jl)
* Econometrics.jl:: [Econometric models in Julia](https://github.com/cgroll/Econometrics.jl).
* GARCH.jl:: [Generalized Autoregressive Conditional Heteroskedastic (GARCH) models](https://github.com/AndreyKolev/GARCH.jl) for Julia.
* Jconometrics.jl :: [MATLAB to Julia port of Spatial Econometrics](https://github.com/adriantorrie/Jconometrics.jl)
* julia__timeseries :: [Time-series analysis functions for Julia](https://github.com/ElOceanografo/julia_timeseries)
* Loss.jl :: [General functions for estimating loss functions](https://github.com/johnmyleswhite/Loss.jl) inspired by Kaggle's release of code for many common metrics.
* TimeSeries.jl:: [Time-series toolkit](https://github.com/JuliaStats/TimeSeries.jl) for Julia.
* TimeModels.jl:: [Modeling time series](https://github.com/JuliaStats/TimeModels.jl) in Julia.
* TimeData.jl:: [package provides fast, robust and convenient representation of time series data](https://github.com/cgroll/TimeData.jl).

    
    
# BENCHMARKS 
* [Microbenchmark timings](http://speed.julialang.org) with a [Timeline](http://speed.julialang.org/timeline/)
* Benchmark.jl :: [A package for computing simple benchmarks, comparing functions and packages](https://github.com/johnmyleswhite/Benchmark.jl)
* BenchmarkLite.jl :: [A lightweight Julia package for simple performance benchmark](https://github.com/lindahua/BenchmarkLite.jl)
   * __TUT__ ::
   * [Notebook showing the usage of BenchmarkLite.jl](http://nbviewer.ipython.org/github/lindahua/BenchmarkLite.jl/blob/master/examples/mathfuns_benchmark.ipynb)
* Criterion.jl :: [A port of the Haskell's Criterion and Clojure's Criterium library](https://github.com/jakebolewski/Criterion.jl) to Julia, that runs benchmarks, analyzing the results using various statistical techniques.
* raytracer.jl :: [Raytracer in the Julia kernel](https://github.com/JuliaLang/julia/blob/master/test/perf/kernel/raytracer.jl) and other [raytracer packages](https://github.com/jakebolewski/rays).
* SimplexBenchmarks :: [Benchmarks comparing individual operations of the Simplex method for linear programming](https://github.com/mlubin/SimplexBenchmarks) in Julia and other languages. Uses modified version of jlSimplex to generate data from real instances.
* SortPerf.jl :: [Julia module to test the performance of sorting algorithms](https://github.com/kmsquire/SortPerf.jl).


### Optimization 
* ampl.jl :: [Julia interface to the AMPL Solver Library (ASL)](https://github.com/dpo/ampl.jl)
* JuliaOpt :: is an [umbrella group for Julia-based optimization-related projects](http://juliaopt.org/), with its own [julia-opt mailing list](https://groups.google.com/forum/#!forum/julia-opt) at Google groups. 
* BlackBoxOptim.jl :: [is an experimental, work-in-progress global optimization framework](https://github.com/robertfeldt/BlackBoxOptim.jl) for Julia, supporting both multi- and single-objective optimization problems, focused on (meta-)heuristic/stochastic algorithms (DE, PSO, CMA-ES etc).
* CPLEX.jl :: [The CPLEX.jl package provides an interface for using IBM's CPLEX Optimizer™ from the Julia language](https://github.com/joehuchette/CPLEX.jl). You cannot use CPLEX.jl without having purchased and installed a copy of CPLEX Optimizer™ from IBM. This package is available free of charge and in no way replaces or alters any functionality of IBM's CPLEX Optimizer product.
* CUTEst.jl :: [Julia interface for CUTEst](https://github.com/lpoo/CUTEst.jl)
* CVX.jl :: [is a julia package for disciplined convex programming](https://github.com/madeleineudell/CVX.jl).
* ECOS.jl :: [Julia wrapper for the ECOS SOCP solver](https://github.com/jfsantos/ECOS.jl)
* Gurobi.jl :: [is a Julia interface for the Gurobi Optimizer](https://github.com/JuliaOpt/Gurobi.jl), a [commercial optimization solver for a variety of mathematical programming problems](https://en.wikipedia.org/wiki/Gurobi), including linear programming (LP), quadratic programming (QP), quadratically constrained programming (QCP), mixed integer linear programming (MILP), mixed-integer quadratic programming (MIQP), and mixed-integer quadratically constrained programming (MIQCP).
* Ipopt.jl :: [is a Julia interface to the Ipopt nonlinear solver](https://github.com/JuliaOpt/Ipopt.jl).
* IProfile :: Use [IProfile in Base to profile your code](http://docs.julialang.org/en/latest/stdlib/profile/). It contains an "instrumenting profiler" for the Julia language and you can see the [IProfile.jl package on github](https://github.com/timholy/IProfile.jl).
* JuliaCMAES:: [CMA-ES port](https://github.com/Staross/JuliaCMAES) - a mix of the original minimal MATLAB implementation (purecmaes.m) and the full one (cmaes.m).
* Junquo.jl :: stands for "[JUlia Nonconvex QUadratically constrained quadratic program Optimizer](http://github.com/IainNZ/Junquo.jl)", a (mixed-integer) nonconvex quadratically constrained quadratic program (QCQP) solver.
* LSQ.jl :: [is a library that makes it easy to formulate and solve least-squares optimization problems with linear equality constraints](https://github.com/davidlizeng/LSQ.jl).
* MOpt.jl :: [Parallel derivative-free Moment Optimization for Julia](https://github.com/floswald/MOpt.jl)
* Mosek.jl :: [Interface to the Mosek solver](https://github.com/JuliaOpt/Mosek.jl) in Julia.
* NLTester :: [Code for benchmarks comparing AMPL, Julia, and YALMIP (MATLAB) for nonlinear modeling](https://github.com/IainNZ/NLTester).
* NLopt.jl :: Package to call the [NLopt nonlinear-optimization library](https://github.com/JuliaOpt/NLopt.jl) from the Julia language.
* Proximal.jl :: [Translation of Parikh and Boyd code for proximal algorithms](https://github.com/johnmyleswhite/Proximal.jl)
* QuickCheck.jl :: is listed in METADATA and [based on QuickCheck specification-based randomized tester](https://github.com/pao/QuickCheck.jl) for Julia. 
  * _DOCS_::
  * [https://quickcheckjl.readthedocs.org/](https://quickcheckjl.readthedocs.org/)
* SCIP.jl by @mlubin :: [is an optimization software for mixed-integer programs](https://github.com/mlubin/SCIP.jl)
* SCIP.jl by @ryanjoneil :: [is a Julia interface to the SCIP solver](https://github.com/ryanjoneil/SCIP.jl)
* SCS.jl :: [Julia Wrapper for SCS (https://github.com/cvxgrp/scs)](https://github.com/karanveerm/SCS.jl)

### Preprocessor
* Precompiler :: [Precompilation in Julia](https://github.com/JuliaLang/julia/blob/master/base/precompile.jl) and its [documentation](http://docs.julialang.org/en/latest/stdlib/base/#Base.precompile)


# OPERATIONS RESEARCH 
* [Solving a Combination Lock Puzzle with JuMP + Julia](http://iaindunning.com/2013/combination-locks.html) and the [HackerNews thread](https://news.ycombinator.com/item?id=6425160).
* CGRASP.jl :: [Continuous Greedy Randomized Adaptive Search Procedure (CGRASP)](https://github.com/tautologico/CGRASP.jl), in Julia.
* CSDP.jl :: [Julia wrapper for the CSDP semidefinite programming solver](https://github.com/joehuchette/CSDP.jl)
* jlSimplex :: [Proof-of-concept implementation of the (dual) simplex algorithm for linear programming in Julia](https://github.com/mlubin/jlSimplex).
* jobshop :: [ The Jobshop (Open Shop Scheduling Problem (OSSP)) problem](https://github.com/stefan-k/jobshop) is solved with evolutionary strategies in Julia.
* Predictors.jl :: https://github.com/dejakaymac/Predictors.jl
* Ranking.jl :: [Tools for ranking in Julia](https://github.com/johnmyleswhite/Ranking.jl)
* RationalSimplex.jl :: [Pure Julia implementation of the simplex algorithm](https://github.com/IainNZ/RationalSimplex.jl)
* SemidefiniteProgramming.jl:: This package provides a Julia interface for [low-level modeling of semidefinite programming problems and for solving semidefinite programs with solvers such as SDPA and CSDP](https://github.com/daviddelaat/SemidefiniteProgramming.jl).
* VRP :: [Vehicle Routing Problem (VRP)](https://github.com/IainNZ/VRP) is a combinatorial optimization and integer programming problem.


##### DOCS and TUTORIALS
* ORSoftwareTools2014 :: [Repository for code/examples/instructions for the MIT course 15.S60 "Software Tools for Operations Research"](https://github.com/IainNZ/ORSoftwareTools2014)
* DG2012Tutorial.jl :: [Simple examples of SGD-style computations in Julia](https://github.com/johnmyleswhite/DG2012Tutorial.jl)


# STATISTICS
* BasicSpace.jl :: [A port of the R "basicspace" package to Julia](https://github.com/johnmyleswhite/BasicSpace.jl
* BayesModels.jl :: [Tools and Building Blocks for Bayesian Modeling and Probabilistic Inference](https://github.com/lindahua/BayesModels.jl)
* Causality.jl :: [A Julia Package for Causal Inference](https://github.com/tfgit/Causality.jl)
* Civecm.jl :: [Cointegration in Vector Error Correction Models](https://github.com/andreasnoackjensen/Civecm.jl) in Julia.
* ConditionalRandomFields.jl :: [Scalable Conditional Random Fields](https://github.com/jperla/ConditionalRandomFields.jl) code for Julia.
* ConjugatePriors.jl :: [Closed form expressions for conjugate priors in Julia](https://github.com/johnmyleswhite/ConjugatePriors.jl)
* CrossDecomposition.jl :: [Canonical-Correlation Analysis (CCA)](https://github.com/simonster/CrossDecomposition.jl)
* DataFrames.jl :: [A Library for working with tabular data in Julia](https://github.com/juliastats/DataFrames.jl)
   * _DOCS_:: The [DataFrames manual section on IO](http://juliastats.github.io/DataFrames.jl/io.html).
* DataArrays.jl :: This package [extends Julia by introducing data structures that can contain missing data](https://github.com/JuliaStats/DataArrays.jl).
* DataFramesMeta.jl :: [Metaprogramming tools for DataFrames](https://github.com/JuliaStats/DataFramesMeta.jl).
* DimensionalityReduction.jl :: [Methods for dimensionality reduction](https://github.com/JuliaStats/DimensionalityReduction.jl)
* DiscreteFactor.jl :: [Discrete factor and its operations in Probabilistic Graphical Models](https://github.com/wlbksy/DiscreteFactor.jl)
* DiscreteInference.jl :: [Viterbi algorithm](https://github.com/lindahua/DiscreteInference.jl).
* DiscriminantAnalysis.jl :: [Methods for discriminant analysis](https://github.com/johnmyleswhite/DiscriminantAnalysis.jl), in Julia.
* Distance.jl :: [A Julia package for evaluating distances(metrics) between vectors](https://github.com/JuliaStats/Distance.jl)
* Distributions.jl :: The [Distributions](http://juliastats.github.io/Distributions.jl/index.html) package.
   * _DOCS_:: are available at [distributionsjl.readthedocs.org](http://distributionsjl.readthedocs.org/en/latest/)
* DPMM.jl :: [Dirichlet Process Mixture Models in Julia](https://github.com/sbos/DPMM.jl)
* Earth.jl :: is the wrapper for the stand-alone version of R's [earth package](https://github.com/lendle/Earth.jl). The [Earth package in R](http://cran.r-project.org/web/packages/earth/) for [Multivariate Adaptive Regression Splines](http://en.wikipedia.org/wiki/Multivariate_adaptive_regression_splines) (MARS), a form of regression analysis.
* FeldtLib.jl :: [Comparing two set of samples (empirical distributions)Baumgartner-Weis-Schindler statistic and tests](https://github.com/robertfeldt/FeldtLib.jl)
* GaussianProcesses.jl :: [A port of the Gaussian Processes toolkit to Julia](https://github.com/johnmyleswhite/GaussianProcesses.jl)
* GeometricMCMC.jl :: [Geometric MCMC algorithms and zero-variance (ZV) Monte Carlo Bayesian routines](https://github.com/scidom/GeometricMCMC.jl).
* HyperLogLog.jl :: [A simple HyperLogLog implementation](https://github.com/johnmyleswhite/HyperLogLog.jl) in Julia.
* HypothesisTests.jl :: [T-tests, Wilcoxon rank sum (Mann-Whitney U), signed rank, and circular statistics](https://github.com/simonster/HypothesisTests.jl) in Julia.
* Isotonic.jl :: [This implements several algorithms for isotonic regression in Julia.](https://github.com/ajtulloch/Isotonic.jl)
   * @ajtulloch's blog on [speeding up Isotonic Regression with Julia](http://tullo.ch/articles/python-vs-julia/) and the [IJulia notebook](http://nbviewer.ipython.org/url/gist.githubusercontent.com/ajtulloch/9485996/raw/94b3d0e6bd67256f1f02eebb1463365dbc8b64fc/Julia.ipynb)
* ITC.jl :: [Code for modeling intertemporal choice](https://github.com/johnmyleswhite/ITC.jl) in Julia.
* JAGS.jl: A Julia interface to [JAGS, to provide a shared library as an interface between Julia and JAGS](https://github.com/olofsen/JAGS.jl) - Just another Gibbs sampler.
* Jags.jl :: [Julia package for using Just another Gibbs sampler](https://github.com/goedman/Jags.jl)
* JuMPStoch.jl :: [A stochastic optimization framework for JuMP](https://github.com/joehuchette/JuMPStoch.jl
* KernSmooth.jl :: [is a direct port of the R package KernSmooth, (v2.23-10.), carrying an unlimited license.](https://github.com/lendle/KernSmooth.jl)
* KLDivergence.jl :: [KL-divergence estimation in Julia](https://github.com/johnmyleswhite/KLDivergence.jl)
* KSVM.jl :: [Kernel Support Vector Machine (SVM)](https://github.com/remusao/KSVM.jl) written in Julia.
* LIBSVM.jl :: [Julia bindings for LIBSVM](https://github.com/simonster/LIBSVM.jl)
* LARS.jl :: [Least angle regression](https://github.com/simonster/LARS.jl)
* MCBN.jl :: [Monte Carlo Bayesian averaging over Bayesian networks](https://github.com/binarybana/MCBN.jl)
* MCMC.jl :: is a [generic engine for implementing Bayesian statistical models using Markov Chain Monte Carlo (MCMC) methods](https://github.com/JuliaStats/MCMC.jl). 
* MCMC2.jl :: [Alternative MCMC package design demo](https://github.com/johnmyleswhite/MCMC2.jl)
* MCMCExampleRepository.jl :: [Repository for MCMC Julia examples](https://github.com/goedman/MCMCExampleRepository.jl)
* MCMCModels.jl :: [Scratch space for hosting temporarily current model specification for MCMC inference](https://github.com/scidom/MCMCModels.jl)
* Mamba.jl :: [Markov chain Monte Carlo simulation toolkit for julia](https://github.com/brian-j-smith/Mamba.jl)
* MixedModels.jl :: [A Julia package for fitting (statistical) mixed-effects models](https://github.com/dmbates/MixedModels.jl).
* MixtureModels.jl :: [A Julia package for probabilistic mixture models](https://github.com/lindahua/MixtureModels.jl)
* MultivariateAnalysis.jl :: [A Julia package for multivariate data analysis (e.g. dimension reduction)](https://github.com/lindahua/MultivariateAnalysis.jl)
* NaiveBayes.jl :: [The Gaussian Naive Bayes model](https://github.com/johnmyleswhite/NaiveBayes.jl) in Julia.
* NaiveBayes.jl :: [Simple Naive Bayes implementation in Julia](https://github.com/nutsiepully/NaiveBayes.jl)
* Nonparametric.jl :: [The julia package for nonparametric density estimate and regression](https://github.com/panlanfeng/Nonparametric.jl).
* NHST.jl :: [Null hypothesis significance tests](https://github.com/johnmyleswhite/NHST.jl)
* OpenPP.jl :: [Open Source Probabilistic Programming](https://github.com/JuliaStats/OpenPP.jl) in Julia.
* ParallelSparseRegression.jl :: [A Julia library for parallel sparse regression](https://github.com/madeleineudell/ParallelSparseRegression.jl), that implements solvers for regression problems including least squares, ridge regression, lasso, non-negative least squares, and elastic net; and proposes to add fast methods to obtain regularization paths.
* PGM.jl :: [A Julia framework for probabilistic graphical models.](https://github.com/JuliaStats/PGM.jl)
* PGM0.jl :: [A bottom-up approach to probabilistic graphical models](https://github.com/micklat/PGM0.jl)
* ProbabilisticModeling.jl :: [A BUGS-like language for describing probabilistic models in Julia](https://github.com/johnmyleswhite/ProbabilisticModeling.jl)
* ProbTopicModels.jl :: [Probabilistic topic models](https://github.com/lindahua/ProbTopicModels.jl)
* QuantileRegression.jl :: [Quantile regression in the Julia language](https://github.com/vincentarelbundock/QuantileRegression.jl)
* Queries :: [Composable queries for Julia DataFrames](https://github.com/carljv/Queries)
* RandomProcesses.jl :: [Random processes (CRP, CRT) in Julia](https://github.com/johnmyleswhite/RandomProcesses.jl)
* Ridge.jl :: [Ridge regression and classification](https://github.com/johnmyleswhite/Ridge.jl)
* Rmath.jl :: [Archive of functions that emulate R's d-p-q-r functions for probability distributions](https://github.com/dmbates/Rmath.jl)
* RmathDist.jl :: [This package provides a julia interface to the distributions provided by the standalone Rmath library](https://github.com/JuliaStats/RmathDist.jl), which is part of the R project for statistical computing.
* RunningStats.jl :: [Julia translation of John D. Cook's code for running moment statistics and univariate regressions](https://github.com/johnmyleswhite/RunningStats.jl)
* Sampling.jl :: [Basic sampling algorithms](https://github.com/JuliaStats/Sampling.jl) package, that provides algorithmic support to statistics-related packages, including Distributions.jl
* SGDDemo.jl :: [Stochastic Gradient Descent (SGD) predictive models for large data sets](https://github.com/johnmyleswhite/SGDDemo.jl) in Julia.
* SGD2.jl :: [Stochastic gradient descent, a draft of new methods for SGD calculations](https://github.com/johnmyleswhite/SGD2.jl)
* SimpleMCMC.jl :: [Small framework for MCMC sampling and maximization on user-defined models](https://github.com/fredo-dedup/SimpleMCMC.jl)
* SimpleNets :: [Simple neural nets implementions in Julia](https://github.com/rgehring/SimpleNets)
* SimpleRL.jl :: [A bare-bones package for simulating RL models and estimating them from behavioral data](https://github.com/johnmyleswhite/SimpleRL.jl)
* SmoothingKernels.jl :: [Smoothing kernels for use in kernel regression and kernel density estimation](https://github.com/johnmyleswhite/SmoothingKernels.jl).
* Stan.jl :: [Julia package for using Stan](https://github.com/goedman/Stan.jl). [Stan](http://en.wikipedia.org/wiki/Stan_%28software%29) is a probabilistic programming language for Bayesian inference written in C++, and licensed under the New BSD License. The Stan language is used to specify a Bayesian statistical model, which is an imperative declaration of the log probability density function.
* StatsBase.jl :: is the [Stats meta-package for basic statistics functions](https://github.com/JuliaStats/StatsBase.jl) for Julia.
   * _DOCS_:: Documentation available at [statsbasejl.readthedocs.org](http://statsbasejl.readthedocs.org/en/latest/)
* SVM.jl :: [Native Julia implementations of standard SVM algorithms](https://github.com/JuliaStats/SVM.jl)
* TopicModels.jl :: [TopicModels for Julia](https://github.com/slycoder/TopicModels.jl)

##### DOCS and TUTORIALS
* DCStats.jl :: [IJulia Notebooks that provide a brief introduction to Julia for statistical programming](https://github.com/johnmyleswhite/DCStats.jl)



## Statistical Tests
* RobustStats.jl :: [A collection of robust statistical tests based on the R package WRS (R-Forge repository) by Rand Wilcox](https://github.com/mrxiaohe/RobustStats.jl)
* StatTests.jl :: [A set of statistical tests for Julia](https://github.com/i-kiwamu/StatTests.jl)



## Valuation
**Finance**
* [Julia Quant group on Github](https://github.com/JuliaQuant).
* AssetMgmt.jl :: [Asset Management](https://github.com/cgroll/AssetMgmt.jl)
* FinancialBlotter.jl:: [Financial Instruments and Accounting](https://github.com/JuliaQuant/FinancialBlotter.jl) in Julia.
* FinanceStats.jl :: [An experimental sandbox of functions that implement common statistical methods in finance](https://github.com/JuliaQuant/FinanceStats.jl)
* GLM.jl:: [Linear models (LM's) and generalized linear models (GLM's)](https://github.com/JuliaStats/GLM.jl) in Julia.
* Ito.jl:: An open source [toolkit for financial computing](https://github.com/aviks/Ito.jl) in Julia.
* Lazy.jl:: [Functional programming](https://github.com/one-more-minute/Lazy.jl) for Julia.
* LibTrading.jl :: [The Julia LibTrading package is a wrapper for the libtrading library](https://github.com/StefanKarpinski/LibTrading.jl), which "is an open source API for high-performance, low-latency trading applications."
* MarketTechnicals.jl:: [Technical analysis of financial time series](https://github.com/JuliaQuant/MarketTechnicals.jl) in Julia.
* MCInsurance.jl:: [This Julia package provides multi-period Monte Carlo simulations](https://github.com/mkriele/MCInsurance.jl) for life insurance.
* Pandas.jl:: [A Julia front-end to Python's Pandas package](https://github.com/malmaud/Pandas.jl).
* Quandl.jl:: [Julia api to Quandl open source financial, economic and social datasets](https://github.com/milktrader/Quandl.jl).
* SDE.jl :: [Simulation and inference for Ito processes and diffusions](https://github.com/mschauer/SDE.jl)
* TradeModels.jl:: [Modeling the allocation of resources to markets based on the restraints of objective functions](https://github.com/JuliaQuant/TradeModels.jl).
* TradingSystem.jl :: [Quantitative trading framework in Julia](https://github.com/milktrader/TradingSystem.jl)
* ZVSimulator.jl:: [The ZVSimulator package provides a framework for assessing the zero variance (ZV) principle for Monte Carlo or random sampling via simulation](https://github.com/scidom/ZVSimulator.jl).


# VIDEOS
* [Statistical Models in Julia video by Douglas Bates (@dmbates)](https://www.youtube.com/watch?v=v9Io-p_iymI)
