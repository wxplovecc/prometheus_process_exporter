Generic Process Exporter for Prometheus
=======================================

The aim here is to export metrics for a given list of processes defined in a yaml config. 
For example, to export run statisics for a given list of system daemons. 

*** This is still a work in progress ***


Usage
=====

* Modify config.yml.example and copy to config.yml
* Start the serivce

    ./generic_process_exporter.py /path/to/config.yml


Notes
=====
 
* Build on Ubuntu, for Ubuntu. I expect other types of Linux will also work well


Todo
====

* Better validation of the check_processes list