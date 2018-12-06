Kafka Cloud Calculator
======================

An OpenDocument (Libre Office) spreadsheet for modeling your Kafka clusters based on:

* number of brokers
* topics
    * replication factor
    * expected message throughput
    * message size
    * number of consumer groups

The spreadsheet works out the total throughput on the brokers' network interfaces and checks against a list of possible instance types for your cloud provider, determines the overall cost of the instances per cluster, and highlights whether those instances will be adequate or not.

Allows you to play around with cluster sizes to work out the optimum price depending on node types.
