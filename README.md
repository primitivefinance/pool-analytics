# pool-analytics


# Introduction
`pool-analytics` stores aims to make RMM-01 pool data easily accessible for advanced data analytics and modeling. This repo will include data processing scripts and example notebooks. `pool-analytics` is maintained by [0xEvan](https://twitter.com/evandekim). Please reach out if you want to contribute, ask for feature requests, or any general feedback.

# Directory Organization
TBD

# Dependencies
## data script
* Pandas
* Numpy


# Roadmap
- [ ] Add model notebooks
- [ ] Abstract Data Query Script from notebook into seperate directory
- [ ] Refactor PnL notebook
- [ ] Add more pool features:
  - [ ]  multi-pool Spot Price
  - [ ]  multi-pool PnL
  - [ ]  theoretical LPT payoff value


#How to contribute
We'd love to accept your patches and contributions to this project. There are just a few small guidelines you need to follow.

Submitting a patch
It's generally best to start by opening a new issue describing the bug or feature you're intending to fix. Even if you think it's relatively minor, it's helpful to know what people are working on. Mention in the initial issue that you are planning to work on that bug or feature so that it can be assigned to you.

Follow the normal process of forking the project, and setup a new branch to work in. It's important that each group of changes be done in separate branches in order to ensure that a pull request only includes the commits related to that bug or feature.

To ensure properly formatted code, please make sure to use 4 spaces to indent the code. The easy way is to run on your bash the provided script: ./code_formatter.sh. You should also run pylint over your code. It's not strictly necessary that your code be completely "lint-free", but this will help you find common style issues.

Any significant changes should almost always be accompanied by tests. The project already has good test coverage, so look at some of the existing tests if you're unsure how to go about it. We're using coveralls that is an invaluable tools for seeing which parts of your code aren't being exercised by your tests.

Do your best to have well-formed commit messages for each change. This provides consistency throughout the project, and ensures that commit messages are able to be formatted properly by various git tools.

Finally, push the commits to your fork and submit a pull request. Please, remember to rebase properly in order to maintain a clean, linear git history.


# Repository Citation
If you use this software, please cite it as below.
```
authors:
- family-names: "Kim"
  given-names: "Evan"
title: "pool-analytics"
version: 1.0.0
date-released: 2022-07-19
url: "https://github.com/primitivefinance/pool-analytics"```
