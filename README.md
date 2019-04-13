# docker-md2review

The Docker image of [md2review](https://github.com/takahashim/md2review).

## Installation

```
$ docker pull nomadblacky/md2review
```

## Usage

```
$ docker run -it --rm -v $PWD:/pwd -w /pwd nomadblacky/md2review md2review example.md > example.re
```
