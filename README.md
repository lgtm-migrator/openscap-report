# OpenSCAP Report Generator

[![Scrutinizer Code Quality](https://scrutinizer-ci.com/g/OpenSCAP/openscap-report/badges/quality-score.png?b=master)](https://scrutinizer-ci.com/g/OpenSCAP/openscap-report/?branch=master) [![Language grade: Python](https://img.shields.io/lgtm/grade/python/g/OpenSCAP/openscap-report.svg?logo=lgtm&logoWidth=18)](https://lgtm.com/projects/g/OpenSCAP/openscap-report/context:python) [![Code Coverage](https://scrutinizer-ci.com/g/OpenSCAP/openscap-report/badges/coverage.png?b=master)](https://scrutinizer-ci.com/g/OpenSCAP/openscap-report/?branch=master) [![Build Status](https://scrutinizer-ci.com/g/OpenSCAP/openscap-report/badges/build.png?b=master)](https://scrutinizer-ci.com/g/OpenSCAP/openscap-report/build-status/master) [![Code Intelligence Status](https://scrutinizer-ci.com/g/OpenSCAP/openscap-report/badges/code-intelligence.svg?b=master)](https://scrutinizer-ci.com/code-intelligence) [![Total alerts](https://img.shields.io/lgtm/alerts/g/OpenSCAP/openscap-report.svg?logo=lgtm&logoWidth=18)](https://lgtm.com/projects/g/OpenSCAP/openscap-report/alerts/) [![Language grade: JavaScript](https://img.shields.io/lgtm/grade/javascript/g/OpenSCAP/openscap-report.svg?logo=lgtm&logoWidth=18)](https://lgtm.com/projects/g/OpenSCAP/openscap-report/context:javascript) [![Documentation Status](https://readthedocs.org/projects/openscap-report/badge/?version=latest)](https://openscap-report.readthedocs.io/en/latest/?badge=latest)

Tool for generating report from results of oscap scan.

## Installation

[Learn how to install tool in the documentation.](https://openscap-report.readthedocs.io/en/latest/manual/instalation.html)

## Example usage

This command consumes the ARF file, which is one of the possible standardized formats for the results of SCAP-compliant scanners. You can read about generating ARF report files using OpenSCAP in the OpenSCAP User Manual. Or you can use test arf files from repository [`/tests/test_data`](https://github.com/OpenSCAP/openscap-report/tree/master/tests/test_data).

```bash
oscap-report < ssg-fedora-ds-arf.xml > report.html
```

More information about command line usage in [man page](https://openscap-report.readthedocs.io/en/latest/oscap-report.1.html) (`man oscap-report`) or on [readthedocs](https://openscap-report.readthedocs.io/en/latest/)
