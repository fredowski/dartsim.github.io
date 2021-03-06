---
title: Project Status
last_updated: Oct 11, 2016
keywords: 
sidebar: home_sidebar
permalink: project_status.html
toc: false
---

## Project Status

|                         | Master |
| ------------------------| ------ |
| Build on Ubuntu and Mac | [![Build Status](https://travis-ci.org/dartsim/dart.png?branch=master)](https://travis-ci.org/dartsim/dart) |
| Build on Windows        | [![Build status](https://ci.appveyor.com/api/projects/status/6rta8olo95bpu84r/branch/master?svg=true)](https://ci.appveyor.com/project/jslee02/dart/branch/master) |
| Code Coverage           | [![Coverage Status](https://coveralls.io/repos/github/dartsim/dart/badge.svg?branch=master)](https://coveralls.io/github/dartsim/dart?branch=master) |

## Project Statistics

| Measurement            | v2.6 | v3.0 | v4.3 | v5.1 | v6.0 | v6.1 |
| ---------------------- | ---- | ---- | ---- | ---- | ---- | ---- |
| Lines of code          |  26k |  24k |  39k |  58k |  75k |  67k |
| Lines of comments      |  10k |  10k |  18k |  26k |  34k |  30k |
| Test function coverage |   -  |   -  |   -  |   -  |  51% |  52% |

* Measured using [cloc](http://cloc.sourceforge.net/).
* Since v6.1, we exclude external code from the counting: `cloc dart --exclude-dir=dart/external`
