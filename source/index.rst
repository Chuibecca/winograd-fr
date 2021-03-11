****************************************
Welcome to Wino-fr's documentation page
****************************************

`Winograd Schema Challenge in French <http://commonsensereasoning.org/winograd.html>`_ by researchers at `Lattice <https://www.lattice.cnrs.fr/>`_ and `Laboratoire de Linguistique Formelle <http://www.llf.cnrs.fr/fr/winograd-fr>`_.

.. |check| raw:: html

    <input checked=""  type="checkbox">

.. |uncheck| raw:: html

    <input type="checkbox">

News
----

.. include:: news/index.rst
   :start-line: 3

Data
----
.. toctree::
   :caption: Data generated during our project
   :glob:

   data_template/index

.. include:: data_template/index.rst
   :start-line: 3

Interns
------------------

.. toctree::
   :maxdepth: 1
   :caption: Interns
   :glob:

   xiaoou/index
   emma_template/index

Cette section documente la contribution de Xiaoou Wang au projet Wino-fr.

.. admonition:: Log Xiaoou Wang (2021/02/01 - 2021/07/31)

    |check|  2021-03-01: Revise the original xml file to add english ids and identify the non wino items as `000` by *Xiaoou* -> `winograd_fr_v2.xml`

    |check|  2021-03-08: Clean pmi data to get question answer pairs by *Xiaoou* -> `pmi_frwac_alt_corrected.json` :doc:`xiaoou/01_french_data_cleaning`

    |check|  2021-03-10: Get a french-english linking version and using items instead of schemas by *Xiaoou* -> `pmi_frwac_withid.json` :doc:`xiaoou/02_french_final_json`

    |check|  2021-03-10: Build the complete version from xml by *Xiaoou* -> winofr_final.json :doc:`xiaoou/03_french_finalfinal_json`

    |uncheck|  2021-03-10: Calculate pmi with scraper and compare with Bert no context

.. include:: emma_template/index.rst
   :start-line: 3