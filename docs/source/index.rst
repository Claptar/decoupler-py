decoupleR - Ensemble of methods to infer biological activities
==============================================================

**decoupleR** is a package containing different statistical methods to extract biological activities from omics data within a unified framework. It allows to flexibly test any method with any prior knowledge resource and incorporates methods that take into account the sign and weight it. decoupleR can be used with any omic, as long as its features can be linked to a biological process based on prior knowledge. For example, in transcriptomics gene sets regulated by a transcription factor, or in phospho-proteomics phosphosites that are targeted by a kinase

.. figure:: graphical_abstract.png
   :height: 500px
   :alt: decoupleR’s workflow
   :align: center

   decoupleR contains a collection of computational methods that coupled with 
   prior knowledge resources estimate biological activities from omics data.

Check out the :doc:`usage` section for further information.

.. note::

   This project is under active development.

.. toctree::
   :maxdepth: 1
   :hidden:
   
   usage
   api