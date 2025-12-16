---
layout: default_md
title: Apache Artemis TLP GroupId Migration
title-class: page-title-artemis
type: artemis
---

With the move for Artemis to become an independent Apache project, the Maven groupId for Apache Artemis modules is changing from _org.apache.activemq_ over to _org.apache.artemis_ beginning with the Apache Artemis 2.50.0 release.

## Dependency Update Example

For example, if you used the following dependency declaration in your build:
```xml
    <dependency>
       <groupId>org.apache.activemq</groupId>
       <artifactId>artemis-jms-client</artifactId>
       <version>2.50.0</version>
    </dependency>
```
It should have its groupId updated to instead become:
```xml
    <dependency>
       <groupId>org.apache.artemis</groupId>
       <artifactId>artemis-jms-client</artifactId>
       <version>2.50.0</version>
    </dependency>
```
## Relocation POMs

Relocation POM files are being published to the old _org.apache.activemq_ module locations for a period to allow most usage to continue working even with the old groupId whilst you migrate over.
For example, if you were still using org.apache.activemq:artemis-jms-client:2.50.0 you would expect to see something like below in your Maven build logs, which could be the very reason you are reading this web page:

```
[WARNING] The artifact org.apache.activemq:artemis-jms-client:jar:2.50.0 has been relocated to
org.apache.artemis:artemis-jms-client:jar:2.50.0: Update the groupId in your project build file.
Refer to https://artemis.apache.org/artemis-tlp-groupid-migration for more information.
```
