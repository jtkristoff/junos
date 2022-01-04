# Junos configuration templates

**WARNING**: These templates are far from perfect and have weaknesses that
I never bothered to fix. I am not currently maintaining them, but will
leave them here for posterity. January 2021 - jtk

This public repository contains standard Junos configuration templates.
These configurations are applicable to our environment and maybe no
other.  Only the fool would blindly copy and use these templates
without careful consideration and possible tuning for their local
environment.

Feedback and suggestions welcome using the issue tracker.

* [Bidirectional Forwarding Detection (BFD)](bfd.conf)
* [BGP Monitoring Protocol (BMP)](bmp.conf)
* [DePaul-specific prefix-lists](depaul.conf)
* [Firewall filters](firewall.conf)
* [Flows/IPFIX configuration](flows.md)
* [iBGP configuration](ibgp.conf)
* [BGP LOCAL_PREF policy definitions](localpref.conf)
* [Ingress loopback RE protection filtering](loopback.conf)
* [BGP prefix limits](prefix-limit.conf)
* [Route Origin Validation](rov.conf)
* [BGP route sanitization](sanitize.conf)
* [Junos pprade template text](upgrade.template.txt)
