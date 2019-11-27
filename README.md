
OwlH CHANGELOG

## [Unreleased]

    - Monitor - Alert if monitored log file is not changing, is too big.
    - Monitor - Key actions are registered
    - Monitor - Internal status alerts, email notification and approved
    - API - Curl samples repository
    - API - Authentication 


## [0.11.0] - 2019-11-22

    - Event Enritchment - add tags, pre analysis and post analysis filters.
    - Network IDS - Zeek cluster configuration from UI/API
    - Network IDS - Interface Params configuration from UI/API
    - Monitor - event output file is too big, truncate or rotate
    - Monitor - Internal status alerts, email notification and approved
    - API - Initial Swagger based API documentation
    - Visualization - Rules Visualization and dashboards on Kibana -> master-kibana-master (t-sec or event)
    - Nodes - Sort && filter
    - Nodes - Groups - create, add nodes
    - Nodes - Groups - ruleset assignament to group, sync to group members and merge when a member belongs to more than one group.
    - Nodes - API - Bulk Add
    

## [0.10.1] - 2019-10-25

    - I - Network IDS - Zeek cluster configuration from UI/API
    - I - Monitor - Key actions are registered
    - I - API - Initial Swagger based API documentation
    - I - Visualization - Rules Visualization and dashboards on Kibana -> master-kibana-master (t-sec or event)

## [0.10.0] - 2019-10-11
### Added
    - Open Rules - Rule detail and rule modification from UI/API
    - Open Rules - Search suricata rules by SID or MSG
    - Node Services - Wazuh Agent - Manage logs files to be monitored by from UI/API
    - Node Services - Wazuh Agent - see size and read last 10, 50, 100 lines from any monitored log file
    - Node Services - Analyzer - see size and read last 10, 50, 100 lines from analyzer output file
    - Monitor - Monitor log file for Suricata, Zeek and others. size and last 10, 50, 100 lines
    - OS Support - CentOS, Debian/Ubuntu, Raspbidian

### Bugs
    - Multiple bugs or small improvements to previous functionalities


## [0.9.0] - 2019-09-30
### Added
Network IDS
===========

    - Improved Suricata Service management and configuration from UI.
    - Improved Zeek Service management and configuration from UI.

Software TAP & Traffic Transport Management
===========================================

OwlH Node - Manage Traffic forwarded from remote systems to OwlH Node 
---------------------------------------------------------------------

    - Traffic sent to local Socket from remote system and replayed to a local Network Interface
    - Traffic sent to local Socket from remote system and stored in PCAP file
    - Traffic read from local Network interface and send it to a remote system by socket
    - Traffic from PCAP file to a local Network Interface

OwlH Master - Manage Traffic forwarded from remote systems to OwlH Master 
-------------------------------------------------------------------------

    - Traffic sent to local Socket from remote system and replayed to a local Network interface
    - Traffic sent to local Socket from remote system and stored in PCAP file
    - Dispatch traffic between different OwlH Nodes using NFS resources
    - Traffic forensic with Moloch by listening network interface or reading PCAP files

Open Rules
==========

    - Sync all local rulesets to the right nodes 
    - Add notes to rules

## [0.8.0] - 2019-08-01
### Added

- OwlH Installer software 
- OwlH Client software for linux - software tap control
