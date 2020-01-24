..
  See https://developer.lsst.io/restructuredtext/style.html
  for a guide to reStructuredText writing.

:tocdepth: 2

.. sectnum::

.. note::

   **This technote is not yet published.**

   2019 saw significant changes have taken place in IT. Here we address the team structure and responsibilities. We put forward some planning and start on an estimate to complete for IT.

.. Add content here.
.. Do not include the document title (it's automatically added from metadata.yaml).

Introduction
============

In this document we layout the IT approach to the Rubin Observatory  construction. It will refer to other specific tech notes for details. 

We wish to build a modern approach to IT just close enough to the cutting edge to allow us remain current at the start of operations but preferably not quite the bleeding edge. 
To best support deployment we must have an element of research and development in the IT team.

The general Cyber Infrastructure approach of LSST is layered as in the diagram :ref:`Cyber Infrastructure <fig-ci-lsst>` from :cite:`2019arXiv190713060O`


.. figure:: images/CI-LSST.png
   :name: fig-ci-lsst
   :alt: Vera Rubin Observatory Cyber Infrastructure stack.

Vera Rubin Observatory Cyber Infrastructure stack.

Organization
============
IT north and south and interactions. 
Weekly tag up Monday. 

The physical locations are discussed in :ref:`<physicallocs>`


.. include:: physical.rst
 
.. include:: telescope.rst

.. include:: areas.rst

.. include:: documentation.rst

Interactions/Interface
======================
- T&S
- DM
- OIR LAB

.. include:: openissues.rst
.. rubric:: References

.. bibliography:: local.bib lsstbib/books.bib lsstbib/lsst.bib lsstbib/lsst-dm.bib lsstbib/refs.bib lsstbib/refs_ads.bib
   :style: lsst_aa
