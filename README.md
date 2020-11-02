# Scala/Scala.js and sbt Dockerfile

This repository contains a **Dockerfile** of [Scala](http://www.scala-lang.org), [sbt](http://www.scala-sbt.org),  
[node.js](https://nodejs.org/en/) and Docker CLI. 

The primary purpose of this docker container is to build Scala/Scala.js projects with sbt.


## Content ##

* Base docker image [openjdk](https://hub.docker.com/_/openjdk) 8-jdk-slim
* Sbt 1.3.9
* Scala 2.12.10
* node.js 12
* docker CLI

## Installation ##

1. Install [Docker](https://www.docker.com)
2. Pull [image](https://hub.docker.com/r/ant8e/docker-sbt-scala) from public [Docker Hub Registry](https://registry.hub.docker.com):
```
docker pull ant8e/docker-sbt-scala:0.6
```
## Usage ##

```
docker run -it --rm ant8e/docker-sbt-scala:06
```

## License ##

This code is open source software licensed under the [Apache 2.0 License]("http://www.apache.org/licenses/LICENSE-2.0.html").
