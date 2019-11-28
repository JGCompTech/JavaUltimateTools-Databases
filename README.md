# JavaUltimateTools Databases v2.0.0
[![Build Status](https://travis-ci.org/JGCompTech/JavaUltimateTools-Databses.svg?branch=master)](https://travis-ci.org/JGCompTech/JavaUltimateTools-Databases) [![CircleCI](https://circleci.com/gh/JGCompTech/JavaUltimateTools-Databases.svg?style=svg)](https://circleci.com/gh/JGCompTech/JavaUltimateTools-Databases) [![Language grade: Java](https://img.shields.io/lgtm/grade/java/g/JGCompTech/JavaUltimateTools-Databases.svg?logo=lgtm&logoWidth=18)](https://lgtm.com/projects/g/JGCompTech/JavaUltimateTools-Databases/context:java) [![Maven Central](https://maven-badges.herokuapp.com/maven-central/com.jgcomptech.tools/java-ultimate-tools-databases/badge.svg?style=flat-square)](https://maven-badges.herokuapp.com/maven-central/com.jgcomptech.tools/java-ultimate-tools-databases/) [![Javadocs](http://www.javadoc.io/badge/com.jgcomptech.tools/java-ultimate-tools-databases.svg?style=flat-square)](http://www.javadoc.io/doc/com.jgcomptech.tools/java-ultimate-tools-databases)

Java Ultimate Tools Databases allows for easier connection to databases. It contains the following:
- Hibernate Tools - Allows for easier use of Hibernate without all the overhead and boilerplate code usually required to get Hibernate working.
- DatabaseTools - Contains tools to communicate with a database using JDBC. The goal behind this class is to allow connection with the database and creation of auto-generated SQL statements so manually creating native SQL code is not needed. This includes initial table creation which is not normally included in most database frameworks.
- SQL Statement Builders - Allows for using methods instead of native SQL code to generate Prepared Statements
- And Much More!

**NOTE: This Project Has Now Been Updated To Use Java 11!!!**

# Development
Want to contribute? Great!
Any help with development is greatly appreciated. If you want to add something or fix any issues please submit a pull request and if it is helpful it may be merged. Please check out our [Code of Conduct for Contributors](https://github.com/JGCompTech/JavaUltimateTools/blob/master/code-of-conduct.md).

# Documentation
The documentation for JUT is currently a work in progress and new changes will be occurring soon.
To access the documentation site go to: [https://javatools.jgcomptech.com](https://javatools.jgcomptech.com).
If you would like to view the JavaDoc info, it is hosted at [github.io(Current GitHub Branch)](https://jgcomptech.github.io/JavaUltimateTools-Databases/) and at [javadoc.io(Current Maven Release)](http://www.javadoc.io/doc/com.jgcomptech.tools/java-ultimate-tools-databases). The github.io version is what is stored in the doc folder in the project.

# Download
**[Download v2.0.0](https://github.com/JGCompTech/JavaUltimateTools-Databases/releases/tag/v2.0.0)**

The changelog can be found [here](https://javatools.jgcomptech.com/changelog/)

# Using with Maven
If you are familiar with [Maven](http://maven.apache.org), add the following XML
fragments into your pom.xml file. With those settings, your Maven will automatically download our library into your local Maven repository, since our libraries are synchronized with the [Maven central repository](http://repo1.maven.org/maven2/com/jgcomptech/tools/java-ultimate-tools/).

    <dependencies>
       <dependency>
          <groupId>com.jgcomptech.tools</groupId>
         <artifactId>java-ultimate-tools-databases</artifactId>
         <version>2.0.0</version>
       </dependency>
    </dependencies>

# License
[![Creative Commons License](https://i.creativecommons.org/l/by/4.0/88x31.png)](http://creativecommons.org/licenses/by/4.0/)

JavaUltimateTools by J&G CompTech is licensed under a [Creative Commons Attribution 4.0 International License](http://creativecommons.org/licenses/by/4.0/).

&copy;2020 J&amp;G CompTech
