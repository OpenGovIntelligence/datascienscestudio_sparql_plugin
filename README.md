# datascienscestudio_sparql_plugin
Plug In for Dataiku's DataScienceStudio (DSS) for adding datasets being result of a SPARQL SELECT query

# Context
This plugin allows to add datasets from SPARQL SELECT queries to your DSS data science analytics flows.
More info at: https://www.dataiku.com/
Donwloads at: https://www.dataiku.com/dss/trynow/

# Prerequisites
* DSS installed and running
* SPARQLWrapper Python library installed
  see: https://doc.dataiku.com/dss/latest/python/packages.html

# How to install the plugin
See: https://doc.dataiku.com/dss/latest/plugins/offline_install.html

# Using the plugin
When adding a new dataset in a project, the Plugin SPARQL SELECT is added to the list of possibilities.

The plugin takes two parameters:
* the SPARQL enbpoint URL
* the SPARQL query
