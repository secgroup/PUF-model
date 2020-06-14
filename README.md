# PUF-model

Formal model of PUF-based protocols.

This repository contains the [Tamarin prover](https://tamarin-prover.github.io/) models that we used to specify and check PUF-based protocols described in the paper *Automated Analysis of PUF-based Protocols*, by R. Focardi and F. L. Luccio, that will be presented at [IEEE CSF 2020](https://www.ieee-security.org/TC/CSF2020/) in June 2020.

The original models described in the paper are in the [CSF2020](https://github.com/secgroup/PUF-model/tree/master/CSF2020) subfolder. The models here are new, refined versions of the original ones.

## Prerequisites

To check the model you need to install the [Tamarin prover](https://tamarin-prover.github.io/)

## Usage

Models can be checked with Tamarin as follows:

```bash
$ tamarin-prover --prove model.spthy
```

