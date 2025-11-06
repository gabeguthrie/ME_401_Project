# Zero-D Otto Cycle (Java)

This repository contains a simple zero-dimensional thermal Otto cycle simulation written in Java.
The simulation computes the heat per cycle needed to achieve **50 kW** net shaft power and
then time-integrates the gas energy equation to estimate instantaneous and mean shaft power.

## Build

Requires Java 17+ and Maven.

```bash
mvn package
