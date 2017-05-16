Commons State of the Union.
===========================

#### Agenda.

* Introduction
* Past
* Present
* Future

### Introduction

* Sharing code.
    * `commons-compress` used by Maven and Ant
    * `commons-crypto` used by Hadoop and Spark.

### How important is Commons?

* Statistics (top 10 downloaded components, maybe transitive dependencies):
    1. junit
    2. commons-lang
    3. commons-collections
* Another statistics engine (github):
    1.  slf4j-api
    2.  junit
    3.  log4j
    4.  servlet-api
    5.  commons-io
    6.  commons-lang
    7.  guava
    8.  Mockito-all
    9.  spring-context
* It's major in the java ecosystem.

### Past.

* How this this project become so important?
* The Jakarta Project
    * Umbrella for all java projects at the ASV.
    * Umbrella projects are bad for communities. A community of sub-communities is a bad process.
    * Notable jakarta projects:
        * Tomcat
        * Maven
        * Ant
        * Lucene
        * Log4j
        * Struts
        * jakarta-commons
* Apache commons was set up, from jakarta-commons, in 2007 with 20 PMCs.

### Structure of the project

* Sandbox.
* Proper.
* Dormant.

### Components without release

* commons-ognl - has 3.X, and 4.X branches
* commons-functor - rushed into this. Accommodation for functional programming in java.
* commons-imaging - trouble getting through the release process

### Housekeeping

* Moving things to dormant (time with no commits and no issues).
    * betwixt
    * modeler
    * primitives
* Migrating to git (slow). GitHub is a really important platform because of the communication paradigm.

### All ASF Committers.

* Change in 2014.
* If we are the common location for code, then all ASF committers should have the ability to commit.

### Fork of commons-math.

* A group of committers bailed out to hipparchus.
* This is thought of as a failure of the PMC.
* Could be a TLP...should be a TLP.

### Vulnerabilities.

* Deserialization of exploit.
* This is your fault for accommodating for binary streams and not sanitizing.
* Feature toggled off this code.

### Future.

* Keeping up to date with Java 9.
* Staying stable.
* Relevant (scala, javascript).
