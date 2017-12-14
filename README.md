# graylog-cb-defense

Graylog Content Pack supporting events from Cb Defense

# Cb Defense Syslog Connector

Utilise the connector from here: https://developer.carbonblack.com/reference/cb-defense/connectors/

# Cb Defense Syslog Connector Config

A slightly modified cb-defense-syslog.conf.example file exists in this repo; this has an updated output template for the Cb Defense Syslog Connector which prefixes logs with "cb_defense|" in order to provide easier matching for application of the extractor.
