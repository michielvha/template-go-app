# Template Go Application

This repository servers as a starting point for each new Go application.

## Overview

Provide an overview of the project

## Dependencies

- The pipeline requires to add a `PGP_PRIVATE_KEY` in the repository secrets
- The `project_name` in the [.goreleaser.yml](.goreleaser.yml) file should be set to match your repo name.


## Features

- Automated versioning with GitVersion, using tags like `0.0.0`.
- Automated container release via custom action, defaults to `ghcr.io`.
- Automated binary release using goreleaser, with signature & multi arch support.

**TODO: rework below badges to be template agnostic, currently lifted from edgectl**

[![Build and Release](https://github.com/michielvha/edgectl/actions/workflows/binary-release.yaml/badge.svg)](https://github.com/michielvha/edgectl/actions/workflows/binary-release.yaml)
[![Release](https://img.shields.io/github/release/michielvha/edgectl.svg?style=flat-square)](https://github.com/michielvha/edgectl/releases/latest)
[![Go Report Card]][go-report-card] 
[![Go Doc](https://pkg.go.dev/badge/github.com/michielvha/edgectl.svg)](https://pkg.go.dev/github.com/michielvha/edgectl)
[![license](https://img.shields.io/github/license/michielvha/edgectl.svg?style=flat-square)](LICENSE)

[Go Report Card]: https://goreportcard.com/badge/github.com/michielvha/edgectl
[go-report-card]: https://goreportcard.com/report/github.com/michielvha/edgectl
[CodeQL]: https://github.com/michielvha/edgectl/actions/workflows/github-code-scanning/codeql/badge.svg?branch=main
[code-ql]: https://github.com/michielvha/edgectl/actions/workflows/github-code-scanning/codeql
[codecov]: https://codecov.io/gh/michielvha/edgectl/branch/main/graph/badge.svg
[code-cov]: https://codecov.io/gh/michielvha/edgectl
