# github-action-template

## project's goal

This repository is a template to be used in Github Action.

It was thought to help in the first configuration by isolating what is exclusive to the main branch and the others.

## project structure

- ```cicd-prd.yml```   
[x] This template is to run exclusively in production environment

- ```cicd-stg-push.yaml```   
[x] run automatically on all pushed commits in all branches except main

- ```cicd-stg-review.yml```   
[x] This template is to run a workflow when a pull request is approved

## Feel free to suggest changes.

