docs-pra
==========

Docs for VMware Tanzu Architecture for Dell EMC VxRail, formerly known as Pivotal Ready Architecture 

## Which branch to use?

**Note**: Provide instructions in your PRs to indicate which branches you want the Docs team to apply your commits to.

DO NOT USE MASTER BRANCH.

| Branch name | Use for... |
|-------------| -------|
| main        | Not used except for this README |
| v3.2.x      | v3.2.x publishes to https://docs-pcf-staging.sc2-04-pcf1-apps.oc.vmware.com/pra/3-2 |
| v3.1.x      | v3.1.x publishes to https://docs-pcf-staging.sc2-04-pcf1-apps.oc.vmware.com/pra/3-1 |
| v3.0.x      | v3.0.x publishes to https://docs-pcf-staging.sc2-04-pcf1-apps.oc.vmware.com/pra/3-0 |
| v2.4.x      | v2.4.0 |
| v2.3.x      | v2.3.0 |
| v2.2.x      | v2.2.0 |
| v2.1.x      | v2.1.0 |
| v2.0.x      | v2.0.1 |
| n/a         | v2.0.0 — PDFed: https://pra-document-releases.s3.us-east-2.amazonaws.com/pra-2.0.0.pdf |

## Style Guide

This is a word list for terminology and word usage specific to the VMware Tanzu Architecture for Dell EMC VxRail docs.

| Word | Explanation |
|------|-------------|
| TA4V | Acronym for VMware Tanzu Architecture for Dell EMC VxRail |


## Run locally

* ```git clone git@github.com:pivotal-cf/docs-layout-repo.git```
* ```git clone git@github.com:pivotal-cf/docs-book-pra.git```
* ```git clone git@github.com:pivotal-cf/docs-pra.git```

```
cd docs-book-pra
gem install bookbindery
bundle install
```

***Note: ruby version 2.5.5***  

## Concourse Pipeline by doc team

* [Pipeline](https://runway-ci.eng.vmware.com/teams/mapbu-docs/pipelines/pra) will bind the documentation set and push to staging environment
* Promotion to production is done by manual trigger
    
