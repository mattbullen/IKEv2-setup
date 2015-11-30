# IKEv2-setup

A script to take Ubuntu Server 14.04 from clean install to fully ready IKEv2 VPN with strongSwan. The server is firewalled, updated and set to automatically apply future updates.

* VPN server identifies itself with a (free) StartSSL web server certificate
* VPN users authenticate with username and password (EAP-MSCHAPv2)

VPN configuration is tested working with OS X 10.11.1, Windows 10, iOS 9.1, and the Android strongSwan client.
