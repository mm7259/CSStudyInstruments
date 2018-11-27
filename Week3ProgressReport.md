# Week 3 Progress Report

* Tested nm again to reveal that rr actually doesn't hang. The problem I was experiencing before must have been because I was missing a preconfiguration

* Tested split and found out that it doesn't check for filetype at all. Verified it further by monitoring CPU usage for ```split /dev/urandom```
