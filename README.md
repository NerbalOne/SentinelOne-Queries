# SentinelOne Queries
This will be a repository of SentinelOne Deep Visibility queries both the Standard Queries and the Power Queries.

## Info
This repository will mainly contain YAML files with it divided by Operating System and the type of queries. This repository and rules/queries were inspired by [SentinelOne-Queries](https://github.com/keyboardcrunch/sentinelone-queries), [Sysmon-Config](https://github.com/ion-storm/sysmon-config/blob/master/sysmonconfig-export.xml), and [S1QL-Queries](https://github.com/SentineLabs/S1QL-Queries).

## YAML Files
```
title:                  -required
description:            -required
author:                 -required
date:                   -required
modified:               -required
mitreID:                -optional
   technique:           -optional
   tactic:              -optional      
   subtechnique:        -optional
operating_system:       -required
query:                  -required
false_positives:        -optional
   - 
tags:                   -optional
   - 
references:             -optional
   -
status:                 -required
```
Right now the status will either be experimental or stable. Experimental means rule is untested and stable means tested and/or verifed by someone.


## Abbreviations
Below are some of the abbreviations I may use throughout this repository.

S1 = SentinelOne\
DV = Deep Visibility\
PQ = Power Query

## Side Note
I'm still learning how to create rules and queries and not all of these have been tested.\
I don't use all of these for STAR rules. Some are just for threat hunting or finding certain events quicker.\
Best practice would be to add MITRE ATT&CK information for all rules but with my lack of knowledge on the framework and lack of time I don't always include it.\
This is still a work in progess and will be updated off and on.
