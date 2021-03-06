# HRD Cloning Implementation

This repository is an implementation of the statistical profiling technique outlined in:

    Maeda, Rafael K.V., et al. "Fast and Accurate Exploration of Multi-level Caches Using Hierarchical Reuse Distance." International Symposium on High Performance Computer Architecture (HPCA), IEEE, 2017.

The implementation is divided up into three parts:

1. A library that can model a sequence of memory requests.
2. An executable that can generate a model file.
3. An executable that can generate a gem5 trace from a model file.
