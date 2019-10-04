
OwlH CHANGELOG

## [Unreleased]
- Rule detail and rule modification from UI
- Zeek cluster configuration from UI
- Wazuh Agent - Manage logs files to monitor from UI
- Wazuh Agent - see last 10, 50, 100 lines from any monitored log file
- Alert if monitorized log file is not changing. 
- check log file for Suricata and Zeek 



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
