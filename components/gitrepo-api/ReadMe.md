Fabric8 Git Repo API
==================

[![Maven Central](https://maven-badges.herokuapp.com/maven-central/io.fabric8/gitrepo-api/badge.svg?style=flat-square)](https://maven-badges.herokuapp.com/maven-central/io.fabric8/gitrepo-api/)
[![Javadocs](http://www.javadoc.io/badge/io.fabric8/gitrepo-api.svg?color=blue)](http://www.javadoc.io/doc/io.fabric8/gitrepo-api)

This library provides a JAXRS 2.0 based Java client API to git based repositories such as <a href="http://gogs.io/">gogs</a> or <a href="http://github.com/">github</a>

### Add it to your Maven pom.xml

To be able to use the Java code in your [Apache Maven](http://maven.apache.org/) based project add this into your pom.xml

             <dependency>
                 <groupId>io.fabric8</groupId>
                 <artifactId>gitrepo-api</artifactId>
                 <version>2.2.101</version>
             </dependency>

### Building

If you clone the source code:

    git clone https://github.com/fabric8io/fabric8.git
    cd fabric8

Then you should be able to build it via:

    cd components/gitrepo-api
    mvn clean test-compile
