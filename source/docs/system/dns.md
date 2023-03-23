# DNS enumeration

DNS enumeration is possible by sending zone transfer requests to the DNS primary server pretending to be a client. DNS enumerating reveals sensitive domain records in response to the request.

## Remediation

* Configure DNS servers not to send DNS zone transfers to unauthenticated hosts.
* Make sure DNS zone transfers do not contain HINFO information.
* Trim DNS zone files to prevent revealing unnecessary information.

## Tools

* [DNS enumeration tools](red-testlab:docs/enum/dns)
