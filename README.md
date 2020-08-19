# enmime

[![GoDoc](https://godoc.org/github.com/malview/enmime?status.svg)][godoc]
[![Build Status](https://travis-ci.org/malview/enmime.svg?branch=master)][build status]
[![Go Report Card](https://goreportcard.com/badge/github.com/malview/enmime)][go report card]
[![Coverage Status](https://coveralls.io/repos/github/malview/enmime/badge.svg?branch=master)][coverage status]

enmime is a MIME encoding and decoding library for Go, focused on generating and
parsing MIME encoded emails. It is being developed in tandem with the
[Inbucket] email service.

enmime includes a fluent interface builder for generating MIME encoded messages,
see the wiki for example [Builder Usage].

API documentation and examples can be found here:
http://godoc.org/github.com/malview/enmime

## Development Status

**Please base PRs off the `develop` branch**, enmime uses `master` for stable
releases. See [CONTRIBUTING.md] for more information.

enmime is approaching production quality: it works but has not been tested with
a wide variety of source data. It's possible the API will evolve slightly
before an official release.

## About

enmime is written in [Go][golang].

enmime is open source software released under the MIT License. The latest
version can be found at https://github.com/malview/enmime

[build status]: https://travis-ci.org/malview/enmime
[builder usage]: https://github.com/malview/enmime/wiki/Builder-Usage
[coverage status]: https://coveralls.io/github/malview/enmime
[contributing.md]: https://github.com/malview/enmime/blob/develop/CONTRIBUTING.md
[inbucket]: http://www.inbucket.org/
[godoc]: https://godoc.org/github.com/malview/enmime
[golang]: http://golang.org/
[go report card]: https://goreportcard.com/report/github.com/malview/enmime
