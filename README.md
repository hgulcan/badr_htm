# ![Numenta Logo](http://numenta.org/images/numenta-icon128.png)  
# htm.java

<br>

[![htm.java awesomeness](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](http://cogmission.ai) [![AGI Probability](https://img.shields.io/badge/AGI%20Probability-97%25-blue.svg)](http://numenta.com/#hero) [![Coolness Factor](https://img.shields.io/badge/Coolness%20Factor-100%25-blue.svg)](https://github.com/numenta/htm.java-examples) [![Build Status](https://travis-ci.org/numenta/htm.java.png?branch=master)](https://travis-ci.org/numenta/htm.java) [![Coverage Status](https://coveralls.io/repos/numenta/htm.java/badge.svg?branch=master&service=github)](https://coveralls.io/github/numenta/htm.java?branch=master) [![Maven Central](https://maven-badges.herokuapp.com/maven-central/org.numenta/htm.java/badge.svg)](https://maven-badges.herokuapp.com/maven-central/org.numenta/htm.java) [![][license img]][license] [![docs-badge][]][docs] [![Gitter](https://badges.gitter.im/Join  
Chat.svg)](https://gitter.im/numenta/htm.java?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge)

<br>

#### [Official](https://github.com/numenta/htm.java/issues/193)  **Java&trade;** version of...
## Hierarchical Temporal Memory [(HTM)](http://numenta.com/learn/principles-of-hierarchical-temporal-memory.html)

**Community-supported & ported from the** [Numenta Platform for Intelligent Computing (NuPIC) ](https://github.com/numenta/nupic) python project.

_**NOTE: Minimum JavaSE version is 1.8**_

<br>

***

#### Demos & Examples: [HTM.java-examples](https://github.com/numenta/htm.java-examples) repository

***

<br>

### Recent News Items...
* **Network API Rework** for [improved input classification!](http://www.cogmission.ai/2015/10/23/putting-out-fires-with-gasoline/) - (10/23/2015)
* **Use HTM.java for the new** [Numenta HTM Challenge!](http://htmchallenge.devpost.com) - (Sept. 18th - Nov.6th)
* **HTM.java Receives newly updated and re-written TemporalMemory and MonitorMixinFramework** - for test reporting and monitoring (08/23/2015)
* [HTM.java Splits off Demo repository](https://github.com/numenta/htm.java-examples) (08/19/2015)
* [HTM.java Receives new Hot Gym Demo](https://github.com/numenta/htm.java-examples/tree/master/src/main/java/org/numenta/nupic/examples/napi/hotgym) (08/15/2015)

### News Archives...
* [HTM.java Receives new Gitter Chat Room] (https://gitter.im/numenta/htm.java) (08/12/2015)
* [HTM.java Receives new **Cortical.io** demo video!] (https://www.youtube.com/watch?v=Y3p02cbdUas) (08/11/2015)
* [HTM.java Receives two new **Cortical.io** demos!](https://github.com/numenta/htm.java/tree/master/src/main/java/org/numenta/nupic/examples/cortical_io) (07/26/2015)
* [HTM.java Now versioned and up on Maven Central!](http://search.maven.org/#search%7Cga%7C1%7Chtm.java) (06/12/2015)
* [HTM.java Recieves New Network API](http://numenta.org/blog/2015/06/08/htm-java-receives-new-network-api.html) (06/08/2015)
* HTM.java is now [**OFFICIAL!**](https://github.com/numenta/htm.java/issues/193) See the [_**announcement**_](http://lists.numenta.org/pipermail/nupic_lists.numenta.org/2015-February/010404.html) (02/25/2015)
* [HTM.java Now Has Anomaly Detection & Anomaly Likelihood Prediction!](https://github.com/numenta/htm.java/wiki/Anomaly-Detection-Module) (02/22/2015)
* [HTM.java Recieves New Benchmarking Tools](http://numenta.org/blog/2015/02/10/htm-java-receives-benchmark-harness.html) (02/2015)
* [HTM.java Reaches Functional Completion](http://numenta.org/blog/2014/12/03/htm-on-the-jvm.html) (12/2014)


### View [Change Log](https://github.com/numenta/htm.java/blob/master/CHANGELOG.md) (Updated! 2015-08-29)
* Change log itemizes the release history.
* Contains an **"Unreleased" section** which lists changes coming in the next release as they're being worked on - (should help users keep in touch with the current evolution of htm.java)

***

For a more detailed discussion of <b>htm.java</b> see: <BR>
* [htm.java Wiki](https://github.com/numenta/htm.java/wiki)
* [Java Docs](http://numenta.org/docs/htm.java/)

See the [Test Coverage Reports](https://coveralls.io/jobs/4164658) - For more information on where you can contribute! Extend the tests and get your name in bright lights!

For answers to more detailed questions, email the [nupic-discuss](http://lists.numenta.org/mailman/listinfo/nupic_lists.numenta.org) mailing list, or chat with us on Gitter.

[![Gitter](https://img.shields.io/badge/gitter-join_chat-blue.svg?style=flat)](https://gitter.im/numenta/public?utm_source=badge)


For more detailed discussions regarding HTM.java specifically, come chat with us here: 

[![Gitter](https://img.shields.io/badge/gitter-join_chat-green.svg?style=flat)](https://gitter.im/numenta/htm.java?utm_source=badge)

See the blog: [Join the Cogmission](http://www.cogmission.ai)

***
<a name="callToArms"></a>
### Call to Arms: [HTM.java needs you!](https://github.com/numenta/htm.java/wiki/Call-To-Arms)

## Goals

The primary goal of this library development is to provide a Java version of NuPIC that has a 1-to-1 correspondence to all systems, functionality and tests provided by Numenta's open source implementation; while observing the tenets, standards and conventions of Java language best practices and development.

By working closely with Numenta and receiving their enthusiastic support and guidance, it is intended that this library be maintained as a viable Java language alternative to Numenta's C++ and Python offerings. However it must be understood that "official" support is (for the time being) currently limited to community resources such as the maintainers of this library and Numenta Forums / Message Lists and IRC:

 * [NuPIC Community](http://numenta.org/index.html#community)

## Usage
**NOTE:** The Java version of NuPIC **requires no installation** - just **USE** it!

Please refer to the [Network API Quick Start Guide](https://github.com/numenta/htm.java/wiki/NAPI-Quick-Start-Guide)

## Development Environment Installation

The following instructions are for setting up a development environment (which is the only installation required)

**NOTE:** For simple intructions see: [INSTALL.txt](https://github.com/numenta/htm.java/blob/master/INSTALL.txt) 

[Eclipse Environment Setup Wiki](https://github.com/numenta/htm.java/wiki/Eclipse-Setup-Tips)

An Eclipse IDE .project and .classpath file are provided so that the cloned project can be easily set up inside of Eclipse. For the time being, the Eclipse IDE is the only "pre-made" project configuration.

In addition, there are "launch configurations" for all of the tests and any runnable entities off of the "htm.java" main directory. These may be run directly in Eclipse by right-clicking them and choosing "run".

## After download by clone or fork:    

Execute a quick sanity check by running all the tests from within the \<path to git repo\>/htm.java
```
gradle check  # Executes the tests and runs the benchmarks

--or--

gradle -Pskipbench check  # Executes the tests w/o running the benchmarks
```
**Note:** Info on installing **gradle** can be found on the wiki (look at #3.) [here](https://github.com/numenta/htm.java/wiki/Eclipse-Setup-Tips)

**Linux Gradle Issues?** [see the wiki here.](https://github.com/numenta/htm.java/wiki/Gradle---JAVA_HOME-Issue-Resolution)

## Project Integration (New)
For tips and insights on how to use the Network API to add HTM's into your own applications, see:

[Quick Start Guide](https://github.com/numenta/htm.java/wiki/NAPI-Quick-Start-Guide)

...and for more in-depth answers see:

[NAPI Overview](https://github.com/numenta/htm.java/wiki/NAPI-In-Depth-Component-Overview)

Here's how to include SNAPSHOT builds:
``` 
<dependency>
    <groupId>org.numenta</groupId>
    <artifactId>htm.java</artifactId>
    <version>0.6.5-SNAPSHOT</version>
</dependency>

You also may need to include a repositories entry:

<repository>
    <id>oss-sonatype</id>
    <name>oss-sonatype</name>
    <url>https://oss.sonatype.org/content/repositories/snapshots/</url>
    <snapshots>
        <enabled>true</enabled>
    </snapshots>
</repository>
```



## For Updates Follow

* [#HtmJavaDevUpdates](https://twitter.com/hashtag/HtmJavaDevUpdates?src=hash)


[license]:LICENSE.txt
[license img]:https://img.shields.io/badge/License-GNU%20Affero-blue.svg

[docs-badge]:https://img.shields.io/badge/API-docs-blue.svg?style=flat-square
[docs]:http://numenta.org/docs/htm.java/
