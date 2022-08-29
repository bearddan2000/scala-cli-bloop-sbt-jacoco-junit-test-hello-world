# scala-cli-bloop-sbt-jacoco-junit-test-hello-world

## Description
A POC for bloop-sbt app using JUnit.
Writes test results to console
and html. The html for `test-results`
is very basic but could probably be
expanded. jacoco report is dumped
to the `reports/jacoco`.

Compiled and ran from build server `bloop`.

# Build note
Dependencies must be compatable with jdk8 or less.

## Tech stack
- bloop
- scala
- bloop-sbt
  - junit
  - jacoco

## Docker stack
- hseeberger/scala-bloop-sbt:11.0.2-oraclelinux7_1.3.5_2.12.10

## To run
`sudo ./install.sh -u`

## To stop
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`

## Credit
- [Build code concept](https://github.com/bloop-sbt/sbt-jacoco)
