# SentinelOne Queries
This will be a repository of SentinelOne Deep Visibility queries both the standard queries and the Power Queries.

## Info
This repository will mainly contain YAML files with it divided by Operating System and the type of queries. This repository and rules/queries were inspiured by [SentinelOne-Queries](https://github.com/keyboardcrunch/sentinelone-queries), [Sysmon-Config](https://github.com/ion-storm/sysmon-config/blob/master/sysmonconfig-export.xml), and [S1QL-Queries](https://github.com/SentineLabs/S1QL-Queries).
Not all rules/queries will be mapped to the MITRE ATTACK Framework. 

## YAML Files
```
title:                  -required
description:            -required
author:                 -required
date:                   -required
modified:               -required
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
```

## Abbreviations
Below are some of the abbreviations I may use throughout this repository.

S1 = SentinelOne\
DV = Deep Visibility\
PQ = Power Query

## Side Note
I'm still learning how to create rules and queries and not all of these have been tested.\
I don't use all of these for STAR rules. Some are just for threat hunting or finding certain events quicker.\
This is still a work in progess and will be updated off and on.
