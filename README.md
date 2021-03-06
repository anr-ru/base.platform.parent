[![Build Status](https://travis-ci.org/anr-ru/base.platform.parent.svg?branch=master)](https://travis-ci.org/anr-ru/base.platform.parent)

## Base.Platform Project

What is **Base.Platform Project**?

Very often when you are just starting a new Java/Spring project you may feel a lack of some tools/libraries/functions
or just ready solutions that improve your speed of writing the code. Probably, you always rewrite the same
convenient approaches in many projects again like comparisons of two possible null values, conversions of a string
to the decimal value, transaction settings or even a framework that works in the EJB environment with a full
support of distributed transactions. You do not need to start it from scratch anymore - just plug them in.

Base.Platform is a tool for a fast creation of Enterprise-ready applications: from basic utilities for simple
operations to a robust EJB environments with a stand for deploying front-end applications.


### Base.Platform Parent

The parent configuration for all Base.Platform projects which include:

* [Base.Utils](https://github.com/anr-ru/base.utils) - basic classes and functions. 
* [Base.Tests](https://github.com/anr-ru/base.tests) - basic classes and functions for writing tests.
* [Base.Services](https://github.com/anr-ru/base.services) - a framework for creating a business logic
* [Base.Facade](https://github.com/anr-ru/base.facade) - a wrapper deploying a business logic to EJB containers.
* [Base.Standalone](https://github.com/anr-ru/base.standalone) - a framework for quick creating command-line applications
* [Base.Web](https://github.com/anr-ru/base.web) - a framework for creating web applications.
* [Base.Docker](https://github.com/anr-ru/base.docker) - basic utilities to work with docker containers from Java.
* [Base.R](https://github.com/anr-ru/base.R) - a framework to launch routines written in the R language.

All artifacts now are stored in packagecloud.io repositories, so can add the following line to you maven **settings.xml**
file:

```xml
<repositories>
    <repository>
      <id>baseplatform</id>
      <name>Base Platform repository</name>
      <url>https://packagecloud.io/ruanr/baseplatform/maven2</url>
      <releases><enabled>true</enabled></releases>
      <snapshots><enabled>true</enabled></snapshots>
    </repository>
  </repositories>
```
