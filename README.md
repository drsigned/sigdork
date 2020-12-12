# sigdork

![made with go](https://img.shields.io/badge/made%20with-Go-0040ff.svg) ![maintenance](https://img.shields.io/badge/maintained%3F-yes-0040ff.svg) [![open issues](https://img.shields.io/github/issues-raw/drsigned/sigdork.svg?style=flat&color=0040ff)](https://github.com/drsigned/sigdork/issues?q=is:issue+is:open) [![closed issues](https://img.shields.io/github/issues-closed-raw/drsigned/sigdork.svg?style=flat&color=0040ff)](https://github.com/drsigned/sigdork/issues?q=is:issue+is:closed) [![license](https://img.shields.io/badge/license-MIT-gray.svg?colorB=0040FF)](https://github.com/drsigned/sigdork/blob/master/LICENSE.md) [![twitter](https://img.shields.io/badge/twitter-@drsigned-0040ff.svg)](https://twitter.com/drsigned)

## Installation

#### From Binary

You can download the pre-built binary for your platform from this repository's [releases](https://github.com/drsigned/sigdork/releases/) page, extract, then move it to your `$PATH`and you're ready to go.

#### From Source

sigdork requires **go1.14+** to install successfully. Run the following command to get the repo

```bash
$ GO111MODULE=on go get -u -v github.com/drsigned/sigdork/cmd/sigdork
```

#### From Github

```bash
$ git clone https://github.com/drsigned/sigdork.git; cd sigdork/cmd/sigdork/; go build; mv sigdork /usr/local/bin/; sigdork -h
```

## Usage

To display help message for sigurlx use the `-h` flag::

```
$ sigdork -h

     _           _            _    
 ___(_) __ _  __| | ___  _ __| | __
/ __| |/ _` |/ _` |/ _ \| '__| |/ /
\__ \ | (_| | (_| | (_) | |  |   < 
|___/_|\__, |\__,_|\___/|_|  |_|\_\ v1.0.0
       |___/

USAGE:
  sigdork [OPTIONS]

OPTIONS:
  -e              search engine (default: google)
  -p              number of pages (default: 1)
  -q              search query
  -t              template query mode (default: false)
```

## Query Templates

The query templates are stored in `~/.sigdorks` as little JSON files.

## Contribution

[Issues](https://github.com/drsigned/sigdork/issues) and [Pull Requests](https://github.com/drsigned/sigdork/pulls) are welcome.