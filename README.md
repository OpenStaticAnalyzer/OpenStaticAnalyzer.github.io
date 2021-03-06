![](https://raw.githubusercontent.com/sed-inf-u-szeged/OpenStaticAnalyzer/master/OpenStaticAnalyzer/doc/logo/OSA_small.png)

# OpenStaticAnalyzer™
Copyright (c) 2004-2018 Department of Software Engineering, University of Szeged, Hungary.

## About

OpenStaticAnalyzer is a source code analyzer tool, which can perform deep static analysis of the source code of complex systems.

The source code of a program is usually its only up-to-date documentation. At the same time, the source code is the exquisite bearer of knowledge, business processes and methodology, accumulated over a long period of time. Source code quality decrease, which happens due to many quick fixes and time pressure, results in the increase of development and testing costs, and operational risks. In spite of this, the source code usually receives hostile treatment and is merely considered as a tool.

OpenStaticAnalyzer provides deep static analysis of source code. Using the results of the analysis, the quality of the analyzed source code can be improved and developed both in the short- and long term in a directed way.

### Product characteristics

The most important product characteristics of OpenStaticAnalyzer are the following:
- Platform-independent command line tools
- Transparent integration into build processes
- Powerful filter management
- Coding issue detection:
    - Metric threshold violations (MetricHunter module)
    - Re-prioritized and carefully selected [PMD] 5.2.3 coding rule violations
    - [FindBugs] 3.0.0 coding rule violations
    - [Pylint] 1.8.2 coding rule violations
    - FxCop coding rule violations
    - [ESLint] coding rule violations
- Clone detection (copy-pasted source code fragments) extended with clone tracking and "clone smells"
    - Syntax-based, so-called Type-2 clones
- Metrics calculation at component, file, package, class, method, and function levels:
    - Source code metrics
    - Clone metrics
    - Coding rule violation metrics
- Supported languages: Java, Python, C#, JavaScript (C/C++ will be available in the near future).

[PMD]:http://pmd.sourceforge.net/
[FindBugs]:http://findbugs.sourceforge.net
[Pylint]:http://www.pylint.org/
[ESLint]:https://eslint.org/

By continuous static analysis, the software developers can:
- reduce the software erosion rate and this way decrease development costs;
- coding problems can be identified before testing, so the number of test iterations and the testing costs can be reduced;
- the number of errors in delivered software can be reduced, so the operational risks can be decreased, increasing the company's reputation.

## License
OpenStaticAnalyzer 4.0 is licensed under the [European Union Public Licence](https://joinup.ec.europa.eu/software/page/eupl) (EUPL) v1.2.

OpenStaticAnalyzer is free software, distributed in the hope that it will be useful, but on an "AS IS" basis, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the LICENSE file for more details.

## Documentation

### User's Guide

[Java](https://github.com/sed-inf-u-szeged/OpenStaticAnalyzer/blob/master/OpenStaticAnalyzer/java/doc/usersguide/md/Main.md)

[Python](https://github.com/sed-inf-u-szeged/OpenStaticAnalyzer/blob/master/OpenStaticAnalyzer/python/doc/usersguide/md/Main.md)

[C#](https://github.com/sed-inf-u-szeged/OpenStaticAnalyzer/blob/master/OpenStaticAnalyzer/csharp/doc/usersguide/md/Main.md)

[JavaScript](https://github.com/sed-inf-u-szeged/OpenStaticAnalyzer/blob/master/OpenStaticAnalyzer/javascript/doc/usersguide/md/Main.md)

## Project site

Further information, source code, and release packages are available at the [project development site](https://github.com/sed-inf-u-szeged/OpenStaticAnalyzer).
