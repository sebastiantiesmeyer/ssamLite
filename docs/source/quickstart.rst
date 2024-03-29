#################
quickstart / tldr
#################


For those of us

- with very little time,
- who know what `SSAM <https://www.nature.com/articles/s41467-021-23807-4>`__ is,
- and just want to get a quick glance at what SSAM-lite can do ...


Installation
============

Click `here <https://github.com/sebastiantiesmeyer/ssamLite/archive/refs/heads/main.zip>`__
to download SSAM-lite-solo as zip, and extract it.


Test data
=========

Download the test data from Zenodo via 

.. code-block:: bash

   wget https://zenodo.org/record/ .... TODO



My first analysis
=================

Open the *index.html* from the unzipped SSAM-lite directory by double-clicking.

Click on **Get going!**

Click on "Coordinates" and select the *coordinates.csv* from the sample data.
Do the same for the "Signatures" (obviously use the *signature.csv* this time, *duh!*)

Time is flying by so we skip the "Parameters" section, leaving them at their default values,
heading straight for "Analysis" and click on "Run Kernel Density Estimation".
Time for a short break now, this step might take 2 mins.

When the KDE has been estimated scroll further down and hit "Infer Cell Types". Done!

That's how easy SSAM-lite is!