---
# An instance of the Experience widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: experience

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 40

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
  - title: Software Engineer Intern
    company: BreezeML
    company_url: 'https://breezeml.ai'
    company_logo: breezeml
    location: Los Angeles, California
    date_start: '2022-10-01'
    date_end: ''
    description: |2-
        Skills include:
        * Go (Programming Language)
        * Kubernetes
        * Amazon Web Services (AWS)

  - title: Research Assistant
    company: The Caesar Research Group
    company_url: 'https://cs.illinois.edu/research/areas/systems-and-networking'
    company_logo: uiuc-logo2
    location: Champaign, Illinois
    date_start: '2021-09-01'
    date_end: '2021-12-31'
    description: |2-
        * Advised by Prof. Matthew Caesar
        * Focused on a large scale Internet of Things (IoT) software research project
        * Worked on Device Emulation

  - title: Research Intern
    company: CreateLab
    company_url: 'https://createlab.cs.illinois.edu'
    company_logo: uiuc-logo
    location: Champaign, Illinois
    date_start: '2021-05-01'
    date_end: '2021-08-31'
    description: |2-
        * Advised by Prof. Yongjoo Park
        * Developed Airphant: a Cloud-native Search Engine with a Statistical Indexing System, which maintains a randomized multi‐layer structure and analyzes over 70k lines of data
        * Implemented components, such as the multi‐layer hash table and the stop word mapper, in Java; unit‐tested tasks with JUnit; peer reviewed Pull Requests; containerized Airphant in Azure
        * Investigated pros and cons of state‐of‐the‐art Learned Index publications to identify possible research directions
        * Resulted in the paper Reaching Cloud Data with Learned Cold Index
design:
  columns: '2'
---
