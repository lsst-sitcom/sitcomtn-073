##############################
Relative Pointing Verification
##############################

.. note::

   **This technote is a work-in-progress.**

Abstract
========

The goal of the test was to evaluate the accuracy of the telescope's pointing during slewing in different directions. 

Introduction
============

During the test, the telescope was kept at a fixed altitude while performing both forward and backward tests to achieve this. In the forward test, the telescope increased azimuth positions (e.g., -180, -90, 0, +90, +180). In the backward test, the movement was reversed (e.g., +180, +90, 0, -90, -180). This ensured that accuracy could be assessed across a range of directional changes.

Forward and reverse grids in azimuth and elevation were taken over several nights in March 2023. This `notebook <https://github.com/cmsaunders/dm_notebooks/blob/main/AzEl_ForwardBackward.ipynb>`__ looks at the relative pointing for the nights of the 21st and the 22nd, which used the same pointing model.

Results
================

The three plots below show the difference between the actual and commanded pointing when slewing backward and forward, as well as the standard deviation for two separate nights in March 2023.

03-21-2023:

.. figure:: /_static/ForwardReverse_03_21.png

03-22-2023:

.. figure:: /_static/ForwardReverse_03_22.png

The standard deviation for all measurements:

.. figure:: /_static/ForwardReverse_std.png

The table below shows the same data in table format:

03-21-2023:

.. include:: /_static/table_0321.txt

03-22-2023:

.. include:: /_static/table_0322.txt

Standard deviations:

.. include:: /_static/table_dAzdElStd.txt
.. Make in-text citations with: :cite:`bibkey`.
.. Uncomment to use citations
.. .. rubric:: References
.. 
.. .. bibliography:: local.bib lsstbib/books.bib lsstbib/lsst.bib lsstbib/lsst-dm.bib lsstbib/refs.bib lsstbib/refs_ads.bib
..    :style: lsst_aa
