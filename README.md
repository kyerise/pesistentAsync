# pesistentAsync
Support for @PersistentAsync java annotation in different platforms

I need to seemlessly call an upload service that should retry in the background across application restarts. Currently in a spring boot 2.10 application on java 8 that will be migrated to java 21 and spring boot 3.x or 3.x so framework agnostic is important but not the most significant.

Currently considering having seperate artifacts for the different platforms
ie: artifactid=1.1-jdk8-spring, 1.1-jdk-jvm, 1.1-jdk8-quarkus

this initial version targets spring 2.10 (which is obsolete) and java 8 (which i think is obsolete) hopefully will evolve quickly.
