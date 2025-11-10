# Template Go Application

This repository servers as a starting point for each new Go application.

## Overview

Provide an overview of the project

## Dependencies

The pipeline requires to add a `PGP_PRIVATE_KEY` in the repository secrets

## Features

- Automated versioning with GitVersion
- Automated container release via custom action, defaults to `ghcr.io`.
- Automated binary release using goreleaser, with signature & multi arch support.