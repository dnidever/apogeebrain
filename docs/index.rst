.. apogeebrain documentation master file, created by
   sphinx-quickstart on Tue Feb 16 13:03:42 2021.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

**********
APOGEEBrain
**********

Introduction
============
|APOGEEBrain| is a package to determine stellar abundances for APOGEE near-infrared spectra using artificial neural network (ANN) models.  The current models are only for giant stars in the range 3000 < Teff < 6000, -0.5 < logg < 3.0, and -2.5 < [M/H] < +0.5.
The 17 elemental abundances are [C/M], [N/M], [O/M], [Na/M], [Mg/M], [Al/M],
[Si/M], [S/M], [K/M], [Ca/M], [Ti/M], [V/M], [Cr/M], [Mn/M], [Co/M], [Ni/M], and [Ce/M].
These are in the range -0.75 < [X/M] < +0.5 for C, N, O, Mg, Si S, Ca, Ti and -0.6 < [X/M] < 0.6 for the rest (Na, Al, K, V, Cr, Mn, Co, Ni, and Ce).

.. toctree::
   :maxdepth: 1

   install
   gettingstarted
   examples
   modules

*****
Index
*****

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`			  
