# SBT Microsite Docker Image

For use with https://47deg.github.io/sbt-microsites/

Sample usage
`docker run -v $(pwd):/root --rm dylanowen/sbt-microsites sbt makeMicrosite`

## Build
`docker build -t dylanowen/sbt-microsites:latest .`

`docker push dylanowen/sbt-microsites:latest`