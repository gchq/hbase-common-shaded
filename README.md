# hbase-common-shaded

This repository provides a shaded version of `org.apache.hbase:hbase-common`:
 
 - It excludes logging, to avoid SLF4J binding errors. 
 - It relocates Jersey 1.x code, so you can use the library in a Jersey 2.x project.