# Introduction

## What?

Enumeration is listing and identifying the specific services and resources that a target offers.

## Why?

Further exploitation of the system. Items of great interest

* Network services that are running but not in use.
* Default user accounts that have no passwords.
* User accounts that have a revealed password.
* Guest accounts that are active.
* Security tokens.

## How?

* Enumerate hosts on the network using Zenmap. Zenmap is a version of Nmap that has a graphical interface.
* Use Zenmap to create a network topology to help identify the network layout.
* Identify the domains using a combination of Whois lookups and DNS profiling. Use tools such as Whois,
Shodan, and recon-ng to collect domain information.
* Try to enumerate users and groups.
* Try to get a list of SMB shares on the system.
* Enumerate uniform resource locators (URLs) and retrieve any web pages.
* Identifying the software running on a system can be tricky. Get creative. For example, use Ncrack to do a dictionary
attack on the administrator account and then supply that as the credentials to a script to see a list of the processes
running on that system.
* Get lists of services running on a system by performing an Nmap scan.
* Try to obtain security tokens.
* Enumerate social media posts by a user with a given IP address by using a tool like `recon-ng`.

