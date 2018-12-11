# Week 4 and 5 Progress Report

* Added a filetype check in split.c
* Ran the tests. But the tests that used /dev/null as a means to check for empty files, were failing, since /dev/null is a character device and my patch checks for that filetype and blocks split from executing. 
* Ended up submitting the patch anyways. Mentioned that I'd gladly change the tests to use a regular empty file, in case the patch gets any kind of green light. Here's the patch: https://bugs.launchpad.net/ubuntu/+source/coreutils/+bug/1807797
