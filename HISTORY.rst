=======
History
=======

0.1.0 (2020-03-20)
-------------------

* Major refactor of code underlying predictive model
* Based on a contribution from @bharathi-srini: replace naive bayes from sklearn by own implementation
* Thus remove dependencies on numpy, scipy, scikit-learn
* Predictions are much faster: 97/s in the old vs. 239/s in the new code base
* Performance identical
* Deprecate support for python 3.5, add 3.8
* Add more strict type checking rules (mypy.ini)
* Force black code formatting, make this a linter step, "black" all code

0.0.47 (2020-02-28)
-------------------

* Allow overlapping matches of regular expression when generating inital stack of "tokens"

0.0.46 (2020-02-26)
-------------------

* Implemented heuristics to detect (albeit imperfectly) military times

0.0.44 (2019-11-05)
-------------------

* Released time corpus
* Implemented training model using ctparse corpus

0.0.43 (2019-11-01)
-------------------

* Added slash as a general separator
* Added ruleTODTOD (to support expression like afternoon/evening)

0.0.42 (2019-10-30)
-------------------

* Removed nb module
* Fix for two digit years
* Freshly retrained model binary file

0.0.41 (2019-10-29)
-------------------

* Fix run_corpus refactoring bug
* Implemented retraining utilities

0.0.40 (2019-10-25)
-------------------

* update develop dependencies
* remove unused Protocol import from typing_extensions

0.0.39 (2019-10-24)
-------------------

* split ctparse file into several different modules
* added types to public interface
* introduced the Scorer abstraction to implement richer scoring strategies

0.0.38 (2018-11-05)
-------------------

* Added python 3.7 to supported versions (fix on travis available)

0.0.8 (2018-06-07)
------------------

* First release on PyPI.
