---
# An instance of the Experience widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: experience

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 30

title: Experience
subtitle:

# Date format for experience
#   Refer to https://wowchemy.com/docs/customization/#date-format
date_format: Jan 2006

# Experiences.
#   Add/remove as many `experience` items below as you like.
#   Required fields are `title`, `company`, and `date_start`.
#   Leave `date_end` empty if it's your current employer.
#   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
experience:
  - title: Research collaboration / Master project 
    company: SFB 1294, University of Potsdam, Potsdam
    company_url: http://dewiljes-lab.com/
    company_logo: Uni_Potsdam_logo
    location: Potsdam
    date_start: '2023-02-01'
    date_end: '2023-08-31'
    description: |2-
        - Analysing and extending existing regime dependent causal discovery algorithms for the non-linear case. Such algorithms are of great importance both in the geosciences and in personalised medicine, where seasons and treatments may change the underlying data generating process.

  - title: Data Science Working Student 
    company: FactoryPal
    company_url: https://www.factorypal.com/
    company_logo: FP_logo
    location: Berlin
    date_start: '2021-12-01'
    date_end: '2023-05-31'
    description: |2-
        - Analysed the adoption of our algorithm recommendations by the shopfloor operators.
        - Researched the regime dependent performance of multiple models and designed a feature for semi-dynamic recommendations that capture the current state of the production line.
        - Day-to-day data science tasks; fixing bugs and implementing features to keep our pipelines running.

  - title: Research and Development Engineer
    company: FFT Produktionssysteme GmbH
    company_url: 'https://www.fft.de/'
    company_logo: FFT_logo
    location: Bremen
    date_start: '2019-06-01'
    date_end: '2021-05-31'
    description: |2-
        - Designed a PCB (Printed Circuit Board) with sensors, display and wireless capability, which is now in the process of getting a CE certification.
        - Conceptualized and developed an IoT sensor and gateway for safer sailplane winch launches. During 2020 we deployed the system in two flight clubs and collected data of over 200 launches.
        - Coordinated the work of three master students during their internships. Also mentored one masters thesis on the use of RFID for logistics.
        - Designed and led the SW architecture of a calibration machine for load cells and force transducers.
        - Contributed to the concept and development of a data management and evaluation tool based on the Odoo framework.
        
  - title: Internship - Engineer in R&D and Embedded Systems
    company: FFT Produktionssysteme GmbH
    company_url: 'https://www.fft.de/'
    company_logo: FFT_logo
    location: Bremen
    date_start: '2018-06-15'
    date_end: '2019-06-01'
    description: |2-
        - Developed a wireless sensor network for structural monitoring of transportation modules.
        - Designed a PCB prototype with sensors, display and wireless capability.
        - Wrote and tested C drivers and libraries for the PCB sensors and display.

design:
  columns: '2'
---
