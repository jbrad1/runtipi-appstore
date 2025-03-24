# Bitcoin Node Manager

Bitcoin Node Manager (BNM) is a lightweight dashboard and control system for your Bitcoin node.

Check out ElextrumX Dashboard if you run an Electrumx Server.

Features
Extensive dashboard with general information about the node, connected peers and the blockchain
Create rules to manage your peers
Ban, disconnect or log peers that waste resources, are slow or run alternative clients (e.g. BCash)
Set global events that trigger the execution of rules, run rules manually or set up a cron job
Overview of all connected peers including country, ISP, client, traffic usage, supported services...
Ban or disconnect peers
Manage a list of web hoster to detect if peer is hosted or private
Manage banned peers
Unban specific peers
Export/Import your ban list
Generate iptables rules (reject banned peers at OS level)
Last received blocks information
Last received forks (orphaned blocks / alternative chains) information
Memory pool statitics
Wallet overview (no functionality, information only)
Requirements
Bitcoin Core 0.19.0.1+
Web Server (Apache, Nginx, PHP Server)
PHP 7.3.0+
curl extension
Docker (Alternative to Web Server and PHP)


