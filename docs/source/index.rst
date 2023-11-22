Using EHR-QC to preprocess electronic medical records for data modelling
========================================================================

This tutorial was presented at the AI+Care conference 2023.


Overview
--------

The integration of electronic health records (EHRs) has opened new avenues for leveraging historical data in predicting clinical outcomes and enhancing patient care. Nonetheless, the existence of non-standardized data formats and anomalies poses significant hurdles in utilising EHRs for digital health research. Additionally, to develop robust and reproducible predictive models, one needs to use data from multiple healthcare sites to account for population wide variations in their modelling approaches. However, institution specific data formats and inherent heterogeneity of EHR data hinders the seamless data harmonisation. To tackle these issues head-on, we introduce EHR-QC, a comprehensive tool comprising two core modules: the Data Standardization Module and the Pre-processing Module.


Instructors
-----------

#. Associate Professor Sonika Tyagi

Sonika is a group leader and an Associate Professor of Digital Health at School of Computational Technologies, RMIT University. Sonika is also a co-investigator in the SuperbugAI flagship project at the Central Clinical School Monash University.

#. Mr. Yashpal Ramakrishnaiah

Yashpal is a PhD student at the Central Clinical School under the supervision of Sonika Tyagi. Yashpal is the primary developer of the EHR-QC toolkit.


Learning Objectives
-------------------

#. Identifying challenges in applying EHR in a research setting
#. Exploring medical records using EHR-QC modules
#. Transforming raw medical records to standard data models or schemas
#. Performing medical concept mapping using r standard vocabulary of choice
#. Exploring various options to clean and pre-process data to make it machine-learning-ready


Prerequisite
------------

Our target audience is biomedical and health data scientists and clinical practitioners. For conceptual understanding of the process,no prior knowledge of the subject is required. To participate in the hands-on tutorial attendees are required to have a prior knowledge of python coding.


Tool dependencies
-----------------

#. Python 3.8 or above
#. Postgres DB (required only for data standardisation, but not for preprocessing)
#. Docker (optional)
#. Access to any EHR data in csv format


Timetable
---------

.. list-table:: Schedule
   :widths: 25 75
   :header-rows: 1

   * - Activity
     - Timings
   * - Lecture
     - 23 Nov 2023 11:00 AM to 11:15 AM
   * - Live Demo
     - 23 Nov 2023 11:15 AM to 11:40 AM
   * - Q&A
     - 23 Nov 2023 11:40 AM to 11:45 AM


If you use this workflow please cite the following journal article
-------------------------------------------------------------------

.. topic:: Citation

   *Yashpal Ramakrishnaiah, Nenad Macesic, Geoffrey I Webb, Anton Y Peleg, Sonika Tyagi (2023) ‘EHR-QC: A streamlined pipeline for Automated Electronic Health Records standardisation and preprocessing to predict clinical outcomes’, Journal of Biomedical Informatics, 147, p. 104509. doi:10.1016/j.jbi.2023.104509.*

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
