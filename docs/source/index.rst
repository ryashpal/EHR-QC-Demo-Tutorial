Using EHR-QC to preprocess electronic medical records for data modelling
========================================================================

This tutorial was presented at the AI+Care conference 2023.

Overview
--------

The integration of electronic health records (EHRs) has opened new avenues for leveraging historical data in predicting clinical outcomes and enhancing patient care. Nonetheless, the existence of non-standardized data formats and anomalies poses significant hurdles in utilising EHRs for digital health research. Additionally, to develop robust and reproducible predictive models, one needs to use data from multiple healthcare sites to account for population wide variations in their modelling approaches. However, institution specific data formats and inherent heterogeneity of EHR data hinders the seamless data harmonisation. To tackle these issues head-on, we introduce EHR-QC, a comprehensive tool comprising two core modules: the Data Standardization Module and the Pre-processing Module.

Instructors
-----------

#. Associate Professor Sonika Tyagi
#. Mr. Yashpal Ramakrishnaiah

Learning Objectives
-------------------

#. Presenting EHR-QC
#. Identifying challenges in applying EHR in a research setting
#. Becoming familiar with the command line interface of EHR-QC
#. Employing EHR-QC for standardising schemas
#. Creating mappings for standard vocabulary concepts with EHR-QC
#. Conducting data exploration and pre-processing through EHR-QC
#. Gaining perspectives on producing machine-learning-ready data

Prerequisite
------------

#. Python 3.8 or above
#. Postgres DB (required only for data standardisation, but not for preprocessing)
#. Docker (optional)
#. Access to any EHR data in csv format


Timetable
---------

.. list-table:: Schedule
   :widths: 10 25 65
   :header-rows: 1

   * - Sl No
     - Timings
     - Activity
   * - 1
     - 23 Nov 2023 11:00 AM to 11:15 AM
     - Lecture
   * - 2
     - 23 Nov 2023 11:15 AM to 11:40 AM
     - Live Demo
   * - 3
     - 23 Nov 2023 11:40 AM to 11:45 AM
     - Q&A

.. topic:: Cite

   *Ramakrishnaiah, Y. et al. (2023) ‘EHR-QC: A streamlined pipeline for Automated Electronic Health Records standardisation and preprocessing to predict clinical outcomes’, Journal of Biomedical Informatics, 147, p. 104509. doi:10.1016/j.jbi.2023.104509.*

.. topic:: Acknowledgements

   .. image:: images/monash.png
      :width: 20 %

   .. image:: images/alfred.png
      :width: 20 %

   .. image:: images/superbugai.png
      :width: 20 %

   .. image:: images/RMIT_University_Logo.png
      :width: 20 %


Contents
--------

.. toctree::
   :maxdepth: 1

   2023_11_aicare
