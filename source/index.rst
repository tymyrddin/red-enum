Lay of the land
===========================================

Move further and deeper into the scanning process to include security scanning. Enumeration is particularly successful in networks that contain unprotected network resources and services.

The distinction between `reconnaissance <https://recon.tymyrddin.dev/>`_ and remote enumeration is an arbitrary grey area, and during enumeration new hosts and/or services may show up, so what you can not find here you may find `there <https://recon.tymyrddin.dev/>`_.

.. image:: _static/images/in-progress.png
  :alt: Forever in progress ...

----

.. toctree::
   :maxdepth: 1
   :includehidden:
   :caption: Preparation

   Build a local testlab <https://testlab.tymyrddin.dev/docs/webapp/README>
   docs/overview.md

.. toctree::
   :glob:
   :maxdepth: 1
   :includehidden:
   :caption: Systems

   docs/system/README.md
   docs/system/netbios.md
   docs/system/snmp.md
   docs/system/ldap.md
   docs/system/ntp.md
   docs/system/smtp.md
   docs/system/dns.md
   docs/system/macos.md
   docs/system/linux.md
   docs/system/windows.md
   docs/system/virtual.md
   docs/system/cloud.md

.. toctree::
   :glob:
   :maxdepth: 1
   :includehidden:
   :caption: Web applications

   docs/app/README.md
   docs/app/scanning.md
   docs/app/database.md
   docs/app/binaries.md
   docs/app/automated.md
   docs/app/api.md

.. toctree::
   :glob:
   :maxdepth: 1
   :includehidden:
   :caption: Vulnerability identification

   docs/vulns/README.md
   docs/vulns/mapping.md
   docs/vulns/prioritisation.md
   docs/vulns/more.md
