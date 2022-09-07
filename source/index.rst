.. Application threat model documentation master file, created by
   sphinx-quickstart on Sun Jun 26 19:02:21 2022.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Making an application threat model
====================================================
Applications in general, and in a wider perspective, software development requires Software-based threat modelling ("//a structured approach that enables you to identify, quantify, and address the security risks associated with an application//").

These are some simplified and generalised notes on how to identify resources that need protection (assets), document security assumptions, identify attack surface and input and output attack vectors, and how to combine these vectors into attack trees (scenarios) with suggestions on possibly useful mitigations.

.. toctree::
   :maxdepth: 1
   :includehidden:
   :caption: Notes

   docs/objectives.md
   docs/overview.md
   docs/decompose.md
   docs/threats.md
   docs/mitigations.md

.. toctree::
   :caption: Links

   Overview threat models <https://tymyrddin.github.io/threat-models/>
   Attack trees <https://tymyrddin.github.io/attack-trees/>
   Building application and CI/CD targets <https://wyrd.tymyrddin.dev/>