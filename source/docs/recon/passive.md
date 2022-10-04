# Passive information gathering

Passive information gathering comes first. It involves collecting public information from the Internet about the
organisation under scrutiny, without invoking any kind of communication with the target systems. The term used for
discovering information from public data sources available on the Internet is open-source intelligence (OSINT)
gathering.

* Website reconnaissance: download, crawl, or scrape it, manually inspect it.
* Social media scraping to discover names, email addresses, phone numbers, biographies.
* Use Google hacking to look for events or articles that give indications of the company’s reputation and security
posture, to locate login pages, web pages that contain the word “intranet”, etc.
* Use WHOIS to discover domain name and IP address information and identify the technical contact and
administrator contact information for that company or domain.
* Use theHarvester to collect information such as names, email addresses, and subdomains, and discover hosts.
* Use Shodan to get a list of the target's publicly available servers and devices with their IP addresses, the
services running on them, and the ports that are open.
* Use Maltego, maybe it comes up with something more.
* Use tools like recon-ng and censys.
* Download documents from the site if any, or from known platforms, and use FOCA to scan
them to collect the hidden metadata.
* Use `nslookup` and `dig` to query DNS for different types of DNS records.

👉 If zone transfers are not refused, make sure to document that in the report.