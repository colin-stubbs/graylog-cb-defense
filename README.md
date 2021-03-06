# Carbon Black Defense Graylog Content Pack

Graylog Content Pack supporting events from Cb Defense

Spawns input on TCP/11000 with appropriate extractors
Includes stream matching all Cb Defense events
Includes dashboard to summarise Cb Defense notifications

# TODO

1. Enrich with human readable severity?

# Cb Defense Syslog Connector

Utilise the connector from here: https://developer.carbonblack.com/reference/cb-defense/connectors/

# Cb Defense Syslog Connector Config

A slightly modified cb-defense-syslog.conf.example file exists in this repo; this has an updated output template for the Cb Defense Syslog Connector which prefixes logs with "cb_defense|" in order to provide easier matching for application of the extractor.

# Salt Stack Based Deployment

Refer to the following formula: https://github.com/colin-stubbs/salt-formula-cb-defense-syslog

# Cb Defense Dashboard Example

The content pack should create a dashboard as below.

![alt text](https://github.com/colin-stubbs/graylog-cb-defense/raw/master/dashboard_example.png "Example Dashboard")
