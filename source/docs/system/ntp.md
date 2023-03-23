# NTP enumeration

An attacker can enumerate the following information by querying an NTP server.

* List of hosts connected to the NTP server
* Internal client IP addresses, hostnames and operating system used

## Remediation

* Restrict the usage of NTP and enable the use of NTPSec, where possible.
* Filter the traffic with IPTables.
* Enable logging for the messages and events.

## Tools

* [NTP enumeration tools](red-testlab:docs/enum/ntp)
