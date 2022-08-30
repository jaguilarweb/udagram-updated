Pipeline_description.md - Explain the differents steps in the pipeline

# Pipeline 

## Overview

A github accout is mandatory

1.- Create a Github repository with the code to deploy
2.- Add config.yml file
3.- Connect your Github account with the CircleCI
4.- Select the repository with your aplication
5.- Provide the branch name that contains the .circleci/config.yml file
6.- Set up the project (click the buttom)

You can see the command execution included in your config.yml file if you click the "build" link.

The steps re:

01.- Spin up environment
02.- Preparing environment variables
03.- Install NodeJS code
04.- Install NPM
05.- Checkout code
06.- Build
07.- Deploy

## Diagram

![](https://github.com/jaguilarweb/udagram/blob/master/documents/pipeline.png)




