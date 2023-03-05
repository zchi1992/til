# Software Analysis
Software Analysis is mainly classifled into 3 categories: Dynamic (at execution time), Static (at compile time), Hybrid.

## Dynamic and Static Analysis
**Dynamic Analysis** cannot discover information that requires observing an unbounded number of paths. But it can conclusively rule out classess of invariants even by running the program once. 

**Static Analysis** typically operates on a intermediate representation of a program, e.g. control-flow graph. Static Analysis tracks *abstract state*. It may miss variables that have concrete values and thus sacrifies completeness. But whenever the analysis says a variable is a concrete it indeed is correct in all runs of the program. We say it is sound.

## Soundness and Completeness
We can trust the correctness of a sound analysis output. But the analysis may improperly say some programs are not correct. A trivial sound analysis outputs false for any program. 

Unsound means it may produce false negatives and Incomplete means it may produce false positive.

We can trust what is excluded from a complete analysis. If it says some program is incorrect then it must be incorrect. But it may say some incorrect programs are correct. A trivial complete analysis outputs true for any program.

## Measuring Test Suite Quanlity
Coverage Metric and Mutation Analysis

