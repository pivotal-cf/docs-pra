docs-pra
==========

Docs for VMware Tanzu Architecture for Dell EMC VxRail, formerly known as Pivotal Ready Architecture 

## Which branch to use?

**Note**: Provide instructions in your PRs to indicate which branches you want Docs to apply your commits to.

DO NOT USE MASTER BRANCH.

| Branch name | Use for… |
|-------------| -------|
| Master      | Not used except for this README |
| v3.0.x      | v3.0.x publishes to https://docs-pcf-staging.cfapps.io/pra/3-0|
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
gem install [local_file_book_binder_10.1.15.gem]
bundle install
bundle exec bookbinder watch
```

***Note: book binder 10.1.15 gem is internally available, not available in public ruby gem site***  
***Note: ruby version 2.5.5***  

## Concourse Pipeline by doc team

* [Pipeline](https://concourse.run.pivotal.io/teams/cf-docs/pipelines/pra) will bind the doc and push to staging environment
* Promotion to product is done by manual trigger
    
