## NodeJS docker images

Provides a base image (based on official `node:4`) that includes a non-root user (`appy`) that owns the global install.

A couple of useful images to include mocha globally installed and a development one with my preferred toolset (`yo`, `gulp`, `pm2`).

## Automated builds using Travis

- kenjones/nodejs:4
- kenjones/nodejs-mocha
- kenjones/nodejs-dev
- kenjones/nodejs:4-slim
- kenjones/nodejs:4-slim-onbuild

