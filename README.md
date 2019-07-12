# ASG ML Comparison Results

*Accompanying Research Paper Pending Publication*

These are the results from running experiments to compare Symbolic Learning and Statistical Learning.  We used Answer Set Grammars and solved these with [ILASP](http://ilasp.com/) for symbolic learning and a Random Forest, General Linear Model and a Fully Connected Feed-Forward Network for statistical learning.

## Benchmark Machine

The results were obtained from a machine with the following set of specifications:

**Hardware**
* Intel Xeon CPU E7-8870  @ 2.40GHz (80 cores)
* 576GB RAM DDR3 1333

**Operating System**
* Fedora 29 (x86_64)
* Kernel 5.1.11-200

**Software**
* python 3.7.3
* keras 2.4.2
* tensorflow 1.14.0 (cpu)
* h2o 3.24.0.5
* pandas 0.23.4
* scikit-learn 0.19.1
* ILASP version 3.4 -- beta 20/04/2019
