# LDAMadeEasy

A package that is meant to make getting a LDA topic model and similarity scoring much easier for my research

## General Package Notes

This package was made using [Poetry](https://python-poetry.org/docs/basic-usage/).

## Package Organization and Usage

This package is organized into different modules:

- The first is dedicated to ingestion and setup of the data
- The second module is dedicated to making similarity measures between document contained in the data
- The third module is dedicated to making an LDA model and using that model to create several visualizations based upon that model

The first module **MUST** be run first. One function (`load_user_parameters`) checks for all of the variables that are required for usage of the other functions in this package. This function will ask the user for inputs that are needed to complete the tasks indicated by the user. These options can also be specified in the script by the user as global variables and then the function will not prompt the user for inputs unless some parameter is still missing.

## Example Use


