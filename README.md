# Grafana dashboards using InfluxDB
This is a collection of dashboards for use with InfluxDB.

* VMware - Performance by Clusters
* VMware - Performance by VMs
* VMware - Disk Latency by Cluster by Day
* VMware - CPU/Memory by Cluster by Day
* VMware - Network Throughput by Cluster by Day
* VMware - Network Throughput by Cluster by Week
* VSAN Overview
* Switch Interfaces
* SQL Servers (MSSQL)
* TV Dashboard 1

The VMware dashboards are made to be used with `vsphere-influxdb-go` : https://github.com/Oxalide/vsphere-influxdb-go

The SQL dashboard must be used with the `sqlserver` telegraf input with version 2 (`query_version = 2`) : https://github.com/influxdata/telegraf/tree/master/plugins/inputs/sqlserver
