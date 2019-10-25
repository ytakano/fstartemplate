# Ubuntu Linux

## Install F*

see https://gist.github.com/ytakano/b95aa3b443dec463dadfe80b739aae77

## Setup Environment Variables

```
export PATH=PATH_TO_FSTAR/bin:$PATH
export FSTAR_HOME=PATH_TO_FSTAR
```

## Compile and Run

```
$ cd src
$ make
$ ./hello.exe
Hello F*!
```

# Docker

## Run Container and Compile F star's source code

### Host

Build a container image and run the container.

```
$ cd docker
$ docker-compose build
$ docker-compose run fstar
```

### Guest Container

Compile an example file, and execute it.

```
# cd src
# make
# ./hello.exe
Hello F*!
```
