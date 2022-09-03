[![Build Status](https://app.travis-ci.com/anr-ru/base.platform.parent.svg?branch=1.x)](https://app.travis-ci.com/anr-ru/base.platform.parent)

## Base.Platform Project

What is the **Base.Platform** project?

Very often when you are just starting a new Java/Spring project you may feel a lack of some tools/libraries/functions
or just ready solutions that improve your speed of writing the code. Probably, you always write over and over again the same
convenient functions and approaches in many projects like comparisons of two possible null values, conversions of a string
to the decimal value, transaction settings, a framework that works in the EJB environment with a full
support of distributed transactions or a ready solution for implementing REST services.

You do not need to start it from scratch anymore - just plug them in.

**Base.Platform** is a tool for a fast creation of Enterprise-ready applications: from basic utilities for simple
operations to robust EJB environments with a ready-to-market framework for RESTful web services. It is based on huge
experience in development of applications for several decades and also contain a full-fledged set of required libraries.

### Base.Platform Parent

The parent configuration for all Base.Platform projects which include:

* [Base.Utils](https://github.com/anr-ru/base.utils) - basic classes and functions.
* [Base.Tests](https://github.com/anr-ru/base.tests) - basic classes and functions for writing tests.
* [Base.Services](https://github.com/anr-ru/base.services) - a framework for creating a business logic.
* [Base.Facade](https://github.com/anr-ru/base.facade) - a wrapper deploying a business logic with the REST API facade to EJB containers.
* [Base.Standalone](https://github.com/anr-ru/base.standalone) - a framework for quick creating command-line applications.
* [Base.Web](https://github.com/anr-ru/base.web) - a framework for creating web applications.
* [Base.Docker](https://github.com/anr-ru/base.docker) - basic utilities to work with docker containers from Java.
* [Base.R](https://github.com/anr-ru/base.R) - a framework to launch routines written in the R language.
* [Base.Config](https://github.com/anr-ru/base.config) - a basic Maven configuration for projects.

All artifacts now are stored in a public gitlab repository, so can add the following line to you maven **settings.xml**
file:

```xml

<repositories>
    <repository>
        <id>base-platform</id>
        <name>Base Platform Repository</name>
        <url>https://gitlab.com/api/v4/projects/39021055/packages/maven</url>
        <releases>
            <enabled>true</enabled>
        </releases>
        <snapshots>
            <enabled>true</enabled>
        </snapshots>
    </repository>
</repositories>
```
