# sbt-docker-example
example/seed for deploying an sbt project as a docker container

See the [Dockerizing Scala](http://blog.codacy.com/2015/07/16/dockerizing-scala/#gs.0fkH6lw) blog. 

## Quick Start

```sh
git clone https://github.com/johannegger/sbt-docker-example.git
cd sbt-docker-example/
sbt docker:publishLocal
docker run -it  sbt-docker-example:1.0
```
