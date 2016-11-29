Test data for GWGEN
===================

This repository is just used as a container for the test data in the gwgen_
repository. It is installed as a submodule in gwgen/tests/test_data. Hence, to
get the data in your cloned gwgen_ repository, type::

    $ git submodule init

Or, to get it right from the beginning::

    $ git clone https://github.com/Chilipp/gwgen.git --recursive

The test data in this repository has been extracted from the [GHCN]_ and
[EECRA]_ databases

References
----------
.. [GHCN] Menne, M. J., Durre, I., Korzeniewski, B., McNeill, S., Thomas, K.,
    Yin, X., Anthony, S., Ray, R., Vose, R. S., Gleason, B. E., and Houston,
    T. G.: *Global Historical Climatology Network - Daily (GHCN-Daily)*,
    Version 3.22, doi:10.7289/V5D21VHZ, http://dx.doi.org/10.7289/V5D21VHZ, 2012a.
.. [EECRA] Hahn, C. andWarren, S.: *Extended Edited Synoptic Cloud Reports from
    Ships and Land Stations Over the Globe, 1952-1996 (with Ship data
    updated through 2008)*, doi:10.3334/CDIAC/cli.ndp026c,
    http://dx.doi.org/10.3334/CDIAC/cli.ndp026c, 1999.

.. _gwgen: https://github.com/Chilipp/gwgen
