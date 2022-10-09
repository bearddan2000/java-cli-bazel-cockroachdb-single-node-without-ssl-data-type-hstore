# java-cli-bazel-cockroachdb-single-node-without-ssl-data-type-hstore

## Description
Creates a small table `dog` that uses
a key value pair data type.

A java bazel build, that connects to single node
cockroach database without ssl.

## Tech stack
- java
- bazel
  - postgres drivers

## Docker stack
- cockroachdb/cockroach:v19.2.2
- l.gcr.io/google/bazel:latest

## To run
`sudo ./install.sh -u`
- [webui](http://localhost:8080)

## To stop
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`

## Credit
[Cockroach setup](https://github.com/s0rg/cockroach-compose)
