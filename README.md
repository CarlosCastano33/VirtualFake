[![CI/CD Pipeline](https://github.com/CarlosCastano33/VirtualFake/actions/workflows/build.yml/badge.svg)](https://github.com/CarlosCastano33/VirtualFake/actions/workflows/build.yml)
[![Quality Gate Status](https://sonarcloud.io/api/project_badges/measure?project=CarlosCastano33_VirtualFake&metric=alert_status)](https://sonarcloud.io/summary/new_code?id=CarlosCastano33_VirtualFake)
[![Bugs](https://sonarcloud.io/api/project_badges/measure?project=CarlosCastano33_VirtualFake&metric=bugs)](https://sonarcloud.io/summary/new_code?id=CarlosCastano33_VirtualFake)
[![Code Smells](https://sonarcloud.io/api/project_badges/measure?project=CarlosCastano33_VirtualFake&metric=code_smells)](https://sonarcloud.io/summary/new_code?id=CarlosCastano33_VirtualFake)
[![Coverage](https://sonarcloud.io/api/project_badges/measure?project=CarlosCastano33_VirtualFake&metric=coverage)](https://sonarcloud.io/summary/new_code?id=CarlosCastano33_VirtualFake)
[![Duplicated Lines (%)](https://sonarcloud.io/api/project_badges/measure?project=CarlosCastano33_VirtualFake&metric=duplicated_lines_density)](https://sonarcloud.io/summary/new_code?id=CarlosCastano33_VirtualFake)
[![Reliability Rating](https://sonarcloud.io/api/project_badges/measure?project=CarlosCastano33_VirtualFake&metric=reliability_rating)](https://sonarcloud.io/summary/new_code?id=CarlosCastano33_VirtualFake)
[![Technical Debt](https://sonarcloud.io/api/project_badges/measure?project=CarlosCastano33_VirtualFake&metric=sqale_index)](https://sonarcloud.io/summary/new_code?id=CarlosCastano33_VirtualFake)


# VirtualFake

Implementation of a Simple App with the next operations:

* Get random nations
* Get random currencies
* Get random Aircraft
* Get application version
* health check

Including integration with GitHub Actions, Sonarqube (SonarCloud), Coveralls and Snyk

### Folders Structure

In the folder `src` is located the main code of the app

In the folder `test` is located the unit tests

### How to install it

Execute:

```shell
$ mvnw spring-boot:run
```
to download the node dependencies

### How to test it

Execute:

```shell
$ mvnw clean install
```

### How to get coverage test

Execute:

```shell
$ mvwn -B package -DskipTests --file pom.xml
```