# Scanning systems

* Enumerate hosts on the network using Zenmap. Zenmap is a version of Nmap that has a graphical interface.
* Use Zenmap to create a network topology to help identify the network layout.
* Try to enumerate users and groups.
* Try to get a list of SMB shares on the system.
* Enumerate uniform resource locators (URLs) and retrieve any web pages.
* Identifying the software running on a system can be tricky. Get creative. For example, use Ncrack to do a dictionary
attack on the administrator account and then supply that as the credentials to a script to see a list of the processes
running on that system.
* Get lists of services running on a system by performing an Nmap scan.
* Try to obtain security tokens.
* Enumerate social media posts by a user with a given IP address by using a tool like `recon-ng`.
* A full scan does a variety of tests to identify vulnerabilities in the system. For example, Nessus can be set to
use a number of plug-ins such as for checking for security issues with Simple Mail Transfer Protocol (SMTP)
and Simple Network Management Protocol (SNMP) services, checking for Linux security issues, and checking for
web server and Windows vulnerabilities, etc. Such scans are considered to be aggressive.
* If red teaming or hired to do a penetration test where the security team is not informed of our presence, we can do
a stealth scan and are to put more effort into choosing specific scanning techniques to avoid detection by the
blue/security team, for example by not scanning the full IP range sequentially, or scanning ports sequentially, and
by using multiple source IP addresses to scan from.
* Compliance scanning by externals has its own rules and requirements. For example, for compliance with the
Payment Card Industry Data Security Standard (PCI DSS) standards, these include:
  * Both internal and external scans must be performed.
  * External scans must be approved by an approved scanning vendor (ASV).
  * Vulnerability scans are to be done quarterly and after any major change to the environment.
  * If critical vulnerabilities are found, they must be remediated and then a new scan done to validate the remediation steps have removed the vulnerability.

When doing a vulnerability scan on target systems, do it multiple times, as an anonymous, non-credentialed
user, and as a credentialed user with and without administrative credentials.

* As a non-credentialed user we are not to see information such as the password policies configured, group
membership, and other configuration settings.
* As a credentialed user with an administrative account, we may get information about the configuration of the
system including vulnerabilities related to user accounts (for example an account called "administrator" or "admin")
and group membership (too many users in the administrators group), missing patches, and password policy configuration
settings.

## Resources

* [Nmap](https://www.kali.org/tools/nmap/)
* [Zenmap](https://www.kali.org/tools/zenmap-kbx/)