# jemecassedaxa.today
Je me casse d'AXA today

Run locally
```
sbt run
```

Run as docker
```
sbt docker:publishLocal
docker run --name jemecasse -p 8080:9000 jemecassedaxatoday:1.0-SNAPSHOT
```
