# lorem: Lorem Ipsum generator

[![License](https://img.shields.io/github/license/skibish/lorem)](https://github.com/skibish/lorem/blob/master/LICENSE)
[![Release](https://img.shields.io/github/v/release/skibish/lorem)](https://github.com/skibish/lorem/releases)
[![GoDoc](https://godoc.org/github.com/skibish/lorem?status.svg)](https://godoc.org/github.com/skibish/lorem)
[![Go Report](https://goreportcard.com/badge/github.com/skibish/lorem)](https://goreportcard.com/report/github.com/skibish/lorem)
[![Go Lang](https://img.shields.io/github/go-mod/go-version/skibish/lorem)](https://golang.org)

Offline Lorem Ipsum generator.
Inspired by [lipsum.com](https://www.lipsum.com).

## Usage

```bash
$ lorem -h
  -ipsum
        Start with "Lorem ipsum dolor sit amet..."
  -number int
        How many <type> to generate (default 5)
  -stats
        Print statistics
  -type string
        What to generate: p (paragraphs); w (words); b (bytes) (default "p")
  -v    Show version and exit
```

## Example

```bash
$ lorem -ipsum -stats > text.txt
STATS:
Words      242
Bytes      2808
Paragraphs 5

$ cat text.txt
# 5 paragraphs of generated Lorem Ipsum

$ lorem -type w -number 3
Nequefusce per elitvivamus.
```

## Installation

Download binary from [releases](https://github.com/skibish/lorem/releases) to `/usr/local/bin/lorem`.

And start it as:

```bash
lorem
```
