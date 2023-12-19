![Build status](https://github.com/pharo-ai/k-means/workflows/CI/badge.svg)
[![Coverage Status](https://coveralls.io/repos/github/pharo-ai/k-means/badge.svg?branch=master)](https://coveralls.io/github/pharo-ai/k-means?branch=master)
[![Pharo version](https://img.shields.io/badge/Pharo-11-%23aac9ff.svg)](https://pharo.org/download)
[![Pharo version](https://img.shields.io/badge/Pharo-10-%23aac9ff.svg)](https://pharo.org/download)
[![Pharo version](https://img.shields.io/badge/Pharo-12-%23aac9ff.svg)](https://pharo.org/download)
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](https://raw.githubusercontent.com/pharo-ai/KMeans/master/LICENSE)

# Description

Implementation of K-means clustering in Pharo.

## How to install it?

To install the project, go to the Playground (Ctrl+OW) in your [Pharo](https://pharo.org/) image and execute the following Metacello script (select it and press Do-it button or Ctrl+D):

```Smalltalk
Metacello new
  baseline: 'AIKMeans';
  repository: 'github://pharo-ai/k-means/src';
  load.
```

## How to depend on it?

If you want to add a dependency on k-means to your project, include the following lines into your baseline method:

```Smalltalk
spec
  baseline: 'AIKMeans'
  with: [ spec repository: 'github://pharo-ai/k-means/src' ].
```

If you are new to baselines and Metacello, check out the [Baselines](https://github.com/pharo-open-documentation/pharo-wiki/blob/master/General/Baselines.md) tutorial on Pharo Wiki.

## Quick start


