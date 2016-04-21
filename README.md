## NodeJS docker images

[![Build Status](https://travis-ci.org/kenjones-cisco/docker-nodejs.svg?branch=master)](https://travis-ci.org/kenjones-cisco/docker-nodejs)

Provides a base image (based on official `node:4`) that includes a non-root user (`appy`) that owns the global install.

A couple of useful images to include mocha globally installed and a development one with my preferred toolset (`yo`, `gulp`, `pm2`).

## Automated builds using Travis

- kenjones/nodejs:4
- kenjones/nodejs-mocha
- kenjones/nodejs-dev   **same as kenjones/nodejs:4-dev just labelled poorly**
- kenjones/nodejs:4-dev
- kenjones/nodejs:4-slim
- kenjones/nodejs:4-slim-onbuild
- kenjones/nodejs:4-alpine
- kenjones/nodejs:4-dev-alpine

