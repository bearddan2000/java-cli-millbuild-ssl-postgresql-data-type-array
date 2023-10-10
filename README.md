# java-cli-millbuild-ssl-postgresql-data-type-array

## Description
Creates a small table `dog` that uses
a text array data type. Arrays can also be
numeric.

A java gradle build, that connects to postgresql database.

Uses self-sign ssl.

## Tech stack
- java
- millbuild
  - log4j
  - postgresql drivers

## Docker stack
- alpine:edge
- postgresql:alpine
- nightscape/scala-mill

## To run
`sudo ./install.sh -u`

## To stop
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`
