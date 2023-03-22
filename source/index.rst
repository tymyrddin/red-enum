Lay of the land
===========================================

The distinction between `reconnaissance <https://red.tymyrddin.dev/projects/recon/en/latest/>`_ and remote enumeration is an
arbitrary grey area, and during enumeration new hosts and/or services may show up, so what you can not find
here you may find `there <https://red.tymyrddin.dev/projects/recon/en/latest/>`_.

----

.. toctree::
   :glob:
   :maxdepth: 1
   :includehidden:
   :caption: System scanning

   docs/system/README.md
   docs/system/overview.md
   docs/system/virtual.md
   docs/system/sqlmap.md

.. toctree::
   :glob:
   :maxdepth: 1
   :includehidden:
   :caption: Host enumeration

   docs/enumeration/README.md
   docs/enumeration/host.md
   docs/enumeration/macos.md
   docs/enumeration/linux.md
   docs/enumeration/windows.md

.. toctree::
   :glob:
   :maxdepth: 1
   :includehidden:
   :caption: Web applications

   docs/app/README.md
   docs/app/scanning.md
   docs/app/binaries.md

.. toctree::
   :glob:
   :maxdepth: 1
   :includehidden:
   :caption: Specific scanning

   docs/more/README.md
   Scanning API's <https://red.tymyrddin.dev/projects/api/en/latest/docs/enum/scanning.html>
   Scanning the cloud <https://red.tymyrddin.dev/projects/cloud/en/latest/docs/enum/scanning.html>

.. toctree::
   :glob:
   :maxdepth: 1
   :includehidden:
   :caption: Automated vulnerability scanning

   docs/automated/README.md
   docs/automated/greenbone.md
   docs/automated/nessus.md
   docs/automated/nikto.md

.. toctree::
   :glob:
   :maxdepth: 1
   :includehidden:
   :caption: Vulnerability identification

   docs/vulns/README.md
   docs/vulns/mapping.md
   docs/vulns/prioritisation.md
   docs/vulns/more.md
