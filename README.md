# PUF-model

Formal model of PUF-based protocols.

This repository contains the [Tamarin prover](https://tamarin-prover.github.io/) models that we used to specify and check PUF-based protocols described in the paper [*Automated Analysis of PUF-based Protocols*](https://ieeexplore.ieee.org/document/9155194), by R. Focardi and F. L. Luccio, that has been presented at [IEEE CSF 2020](https://www.ieee-security.org/TC/CSF2020/) in June 2020.

## Prerequisites

To check the model you need to install the [Tamarin prover](https://tamarin-prover.github.io/)

## Usage

Models can be checked with Tamarin as follows:

```bash
$ tamarin-prover --prove model.spthy
```

