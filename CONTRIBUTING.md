# Contributing

This repository is a fork of the [`github-semantic-version` module](https://github.com/ericclemmons/github-semantic-version) authored by Eric Clemmons. 

## Installation

1. To install this fork via npm: npm install --save-dev @theelbster/github-semantic-version
2. To install the original package via npm, follow the directions in the [`README.md`].

## High level differences

1. Updated some dependencies to more current versions.
2. Added support for overriding the inherited Github user in case CI uses a different name.
3. Pushing to a branch is no longer hardcoded to master branch.

## Quick tips for using with CI such as Jenkins.

1. Assign the "CI" environment variable. It simply needs to exist.
2. Assign your CI user to "GH_USER". If this is unassigned, the user will be inherited from the Github repo.
3. Assign your personal access token to "GH_TOKEN".
