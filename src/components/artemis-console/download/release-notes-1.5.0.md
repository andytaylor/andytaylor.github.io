---
layout: default_md
title: Artemis Console 1.5.0 Release Notes
title-class: page-title-artemis
type: artemis
---

**Note:** As part of [establishing Apache Artemis](/news/artemis-tlp) as an independent project, the [Maven groupId has switched to _org.apache.artemis_](/artemis-tlp-groupid-migration).

## Bugs Fixed

* [ARTEMIS-5677](https://issues.apache.org/jira/browse/ARTEMIS-5677) - Excessive padding in JMX tree in web console
* [ARTEMIS-5743](https://issues.apache.org/jira/browse/ARTEMIS-5743) - Web console status page difficult to read when unauthorized
* [ARTEMIS-5760](https://issues.apache.org/jira/browse/ARTEMIS-5760) - Web console fails with limited users
* [ARTEMIS-5771](https://issues.apache.org/jira/browse/ARTEMIS-5771) - Display creation time for producer

## Improvements

* [ARTEMIS-5417](https://issues.apache.org/jira/browse/ARTEMIS-5417) - JMX Tree Improvements
* [ARTEMIS-5742](https://issues.apache.org/jira/browse/ARTEMIS-5742) - Implement readSpecifiedAttributes method
* [ARTEMIS-5772](https://issues.apache.org/jira/browse/ARTEMIS-5772) - Hardcoded refresh rate for broker information
* [ARTEMIS-5788](https://issues.apache.org/jira/browse/ARTEMIS-5788) - Create Artemis Tree Processor for JMX tree in the console

## Tasks

* [ARTEMIS-5810](https://issues.apache.org/jira/browse/ARTEMIS-5810) - rename and rebrand the console to reflect the new TLP

## Dependency Upgrades

* [ARTEMIS-5774](https://issues.apache.org/jira/browse/ARTEMIS-5774) - Bump web console to Jetty 12.1.4
* [ARTEMIS-5791](https://issues.apache.org/jira/browse/ARTEMIS-5791) - Upgrade js-yaml to 3.14.2
* [ARTEMIS-5792](https://issues.apache.org/jira/browse/ARTEMIS-5792) - upgrade node-forge to 1.3.2
* [ARTEMIS-5793](https://issues.apache.org/jira/browse/ARTEMIS-5793) - upgrade express to 4.22.1
* [ARTEMIS-5794](https://issues.apache.org/jira/browse/ARTEMIS-5794) - upgrade mdast-util-to-hast to 13.2.1
* [ARTEMIS-5796](https://issues.apache.org/jira/browse/ARTEMIS-5796) - Upgrade glob to 10.5.0