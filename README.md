# java-cli-maven-failsafe-pmd-jacoco-cucumber-testng-hello-world

## Description
A POC for maven app using testNg
and cucumber framework with surefire,
jacoco, pmd, and failsafe plugins.

## Tech stack
- java
- maven
  - testNg
  - jacoco
  - failsafe
  - surefire
  - cucumber
  - pmd

## Docker stack
- maven:3-openjdk-17

## To run
`sudo ./install.sh -u`
- pmd report found at bin/target/site

## To stop
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`

## Credit
- [Code concept](https://stackoverflow.com/questions/67847818/maven-junit-5-cucumber-not-running-tests)
- [Build concept](https://github.com/citrusframework/citrus-samples/blob/main/samples-junit/sample-junit5/pom.xml)
