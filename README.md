# PUF-model

Formal model of PUF-based protocols

This repository contains the [Tamarin prover](https://tamarin-prover.github.io/) models that we used to specify and check PUF-based protocols in the paper "Automated Analysis of PUF-based Protocols" that will be presented at IEEE CSF 2020.

## Prerequisites

To check the model you need to install [Tamarin prover](https://tamarin-prover.github.io/)

## Usage

Models can be checked with Tamarin as follows:

```bash
$ tamarin-prover --prove model.spthy
```
