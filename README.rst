NuSTAR SINGs
=============

~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
NuSTAR Search for INteresting Gamma-ray Signals (SINGS)
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

.. image:: https://www.nustar.caltech.edu/rails/active_storage/representations/redirect/eyJfcmFpbHMiOnsibWVzc2FnZSI6IkJBaHBBcGNNIiwiZXhwIjpudWxsLCJwdXIiOiJibG9iX2lkIn19--ce6097d828c78d38715de028dcc312fd0a024282/eyJfcmFpbHMiOnsibWVzc2FnZSI6IkJBaDdCem9MWm05eWJXRjBPZ2hxY0djNkMzSmxjMmw2WlVraURURXdNalI0TnpZNUJqb0dSVlE9IiwiZXhwIjpudWxsLCJwdXIiOiJ2YXJpYXRpb24ifX0=--22e6756c79e54fff34d7d04b1f622b45e8185a60/nustar_artistconcept_2.jpg
    :target: http://www.nustar.caltech.edu
    :alt: NuSTAR

Rationale and Scope
-------------------

This repo contains the GRB search algorithms used for the NuSTAR SINGS program.

The intent is to split this repo into a "Legacy" archive (for searches prior to 2026)
vs "active" development. The "Legacy" archive contains the code used for the blind
search identification listed in numerous GCN notices for NuSTAR. However, we note that
a large number of the entries in the online NuSTAR GRB database are spurious events.

The web archive of all triggers can be found on `The NuSTAR SINGS Page. <https://nustarsoc.caltech.edu/NuSTAR_Public/grbs/>`_ 

We intend to update this repo, the REDAME file, and the public-facing reports in the
future to limit confusion.

In general, this repo is not intneded to be installed as a stand-alone package, as it is
mainly a selection of scripts that use things like nustar-gen-utils for NuSTAR-specific
tasks as well as standard tools like astropy/scipy/etc.

This script is only intended to be run on a server at the NuSTAR SOC, since it relies on
a number of databases to be available for reading.

