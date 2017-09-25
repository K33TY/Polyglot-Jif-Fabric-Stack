# Polyglot-Jif-Fabric Stack
Installation configurations that work on Mac OSX. 

[TL;DR Skip Down to Installation instructions](https://github.com/K33TY/Polyglot-Jif-Fabric-Stack/blob/master/README.md#prerequisites)

### Information about this Stack

 * [Polyglot](https://www.cs.cornell.edu/projects/polyglot/)
 * [Jif](https://www.cs.cornell.edu/jif/)
 * [Fabric](https://www.cs.cornell.edu/projects/fabric/)

### Installation Backstory

I previously attempted to install this environment on Mac OS Yosemite 10.10.5, but I ran into multiple configuration issues. I could not run Polyglot on the commandline due to [Java Toolprovider](https://docs.oracle.com/javase/7/docs/api/javax/tools/ToolProvider.html) continuously returning null regarding there being a compiler, even when my classpaths and paths were correctly configured and a javac was in the bin directory. I managed to run Polyglot for some reason on Eclipse, but I could not figure out why this was operating differently than from the commandline. However, in attempting to install Jif, Eclipse was no longer recognizing that Polyglot had been built and could access the Toolprovider. 

---

## Prerequisites

The current specifications used for this installation. (It is probable that different operating systems and earlier/later versions of Java JDK will work, but I managed with the following settings.)

* Mac OS Sierra 10.12.6
* Oracle Java JDK v 1.8.0_101-b13

## Ant

## Polyglot


## Jif

## Fabric
