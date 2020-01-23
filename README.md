# Example AuditJS Repo

[![CircleCI](https://circleci.com/gh/sonatype-nexus-community/example-auditjs-repo.svg?style=svg)](https://circleci.com/gh/sonatype-nexus-community/example-auditjs-repo)

[![Build Status](https://travis-ci.org/sonatype-nexus-community/example-auditjs-repo.svg?branch=master)](https://travis-ci.org/sonatype-nexus-community/example-auditjs-repo)

This repo contains examples on how to use AuditJS in:

- CircleCI

Soon it will contain examples for:

- Jenkins
- TravisCI
- GitHub Actions

## Usage in CircleCI

Please refer to the [.circleci/config.yml](https://github.com/sonatype-nexus-community/example-auditjs-repo/blob/master/.circleci/config.yml) for a working config on using `auditjs` in CircleCI.

NOTES:

- We run auditjs using `npx` as this prevents a global install. If you want it to be longer lived, you can install globally.
- We use `--xml` to output a JUnit type XML test result format, and then save that so that you can view vulnerable dependencies as test failures. This is entirely a suggestion, you do not need to do that if you don't want to.

## Usage in TravisCI

Please refer to the [.travis.yml](https://github.com/sonatype-nexus-community/example-auditjs-repo/blob/master/.travis.yml) for a working config on using `auditjs` in TravisCI.

NOTES:

- We run auditjs using `npx` as this prevents a global install. If you want it to be longer lived, you can install globally.

## The Fine Print

This repo is meant for informational purposes, copy-pasta at your own risk :)

You can get to the main `auditjs` repo by clicking [here](https://github.com/sonatype-nexus-community/auditjs).
