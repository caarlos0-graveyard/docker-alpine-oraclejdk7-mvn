# docker-alpine-oraclejdk7-mvn [![](https://badge.imagelayers.io/caarlos0/alpine-oraclejdk7-mvn.svg)](https://imagelayers.io/?images=caarlos0/alpine-oraclejdk7-mvn 'Get your own badge on imagelayers.io')

This image is based on Alpine Linux image, which is only a 5MB image, and contains
[OracleJDK 7](http://www.oracle.com/technetwork/java/javase/overview/index.html)
with [Apache Maven](https://maven.apache.org/) 3.2.5 bundled within.

## Usage Example

```sh
$ cd my/jdk7/project
$ docker run --rm -v `pwd`:/tmp --workdir /tmp caarlos0/alpine-oraclejdk7-mvn \
  mvn clean install
```
