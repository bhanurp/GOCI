# JFrog Pipelines Template - Go

This template simplifies CI pipeline for any Go based projects. It allows to perform all major actions of CI.

----

## Features
- The most commonly used go tools are used for achieving linting and code analysis.
- This template is precise and does the job of setting up CI for the go application quickly.
- Set the steps as optional in case it doesn't suit your project.
- User can change the commands or actions performed in step via values.yml.
- Works for both powershell and bash commands based on OS.
----

## Pre-requisites
- Artifactory Integration
- Pipelines resource for the git repository.
- Xray up and running in case of scan required

----

## Usage
import this template into pipelines yaml to quickly test CI for your Go based project.

----

## Pipelines Details
### Pipeline
Pipelines name is defined in the templateId 

### Resources
Git resource will be the git repository which needs CI. Resources are expected to be created in Pipelines


