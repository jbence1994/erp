erp
===

### Enterprise resource planning application.

[![Continuous integration](https://github.com/jbence1994/erp/actions/workflows/build.yml/badge.svg)](https://github.com/jbence1994/erp/actions/workflows/build.yml)

Prerequisites
-------------

To avoid any unexpected application behaviour, make sure you have installed the following tools with the proper version numbers:

- [Eclipse Temurin JDK 21](https://adoptium.net/temurin/releases/?version=21)
- [Maven 3.9.6](https://maven.apache.org/download.cgi)

Running project locally
-----------------------

### Start application

```bash
mvn clean install

mvn spring-boot:run -Dspring-boot.run.profiles=default
```
