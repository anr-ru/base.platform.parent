[![Build Status](https://travis-ci.org/anr-ru/base.platform.parent.svg?branch=master)](https://travis-ci.org/anr-ru/base.platform.parent)

## Base.Platform Project

What is **Base.Platform Project**?

Very often when you start a new project Java/Spring project you may feel a lack of some tools/libraries/functions
or just ready solutions that improve your speed of writing the code. You probably always rewrite the same
convenient approaches in many projects again like comparisons of two possible null values, conversions of a string
to the decimal value, transaction settings or even a framework that works in the EJB environment with full
support of distributed transactions but you are not required to start it from scratch - just plug it.

Base.Platform is a tool for a fast creation of Enterprise-ready applications: from basic utilities for simple
in-code operations to a robust EJB environments with a stand for deploying front-end applications.

### Base.Platform Parent

The parent configuration for all Base.Platform projects:

* [Base.Utils](https://github.com/anr-ru/base.utils) - basic classes and functions. 
* [Base.Tests](https://github.com/anr-ru/base.tests) - basic classes for writing tests.
* [Base.Services](https://github.com/anr-ru/base.services) - a framework for creating a business logic
* [Base.Facade](https://github.com/anr-ru/base.facade) - a wrapper deploying the business logic to EJB.
* [Base.Standalone](https://github.com/anr-ru/base.standalone) - a framework for quick crearing command-line applications
* [Base.Web](https://github.com/anr-ru/base.web) - a framework for creating web applications.
* [Base.Docker](https://github.com/anr-ru/base.docker) - basic utilities for working with docker containers from Java.
* [Base.R](https://github.com/anr-ru/base.R) - a framework for running routines written on R language.

All artifacts now are stored in packagecloud.io repositories, so can add the following line to you maven **settings.xml**
file:

```xml
<repositories>
    <repository>
      <id>anr-ru</id>
      <name>ANR-RU Public repository</name>
      <url>https://packagecloud.io/ruanr/baseplatform/maven2</url>
      <releases>
        <enabled>true</enabled>
      </releases>
      <snapshots>
        <enabled>true</enabled>
      </snapshots>
    </repository>
  </repositories>
```
