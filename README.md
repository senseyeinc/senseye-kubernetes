# Senseye Helm repository

This repository contains all of Senseye's helm charts.

More to come later

# Available helm charts
These helm charts are meant for internal use. For these charts to work, a few secrets are assumed to exist in their respective namespaces

Required Secrets:

* senseye-ssl-certs: Senseye's wildcard ssl cert
* docker-secret: Senseye's docker login creds


** Expand on this more **

## Grove
This deploys a dask cluster on top of a grove image for distributed computing

** Define all configurable variables here **

## Eucalyptus
Senseye's public facing repo

** Define all configurable variables here **


## Senseye-artemis
System Integrity's artemis package

** Define all configurable variables here **

