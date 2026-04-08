---
title: Informacion sobre bases de datos de virus
date: 2026-04-07T23:27:00
draft: false
---

## Abstract

### Motivation

Influenza A viruses frequently cause seasonal outbreaks and pandemics due to their genetic diversity and reassortment potential. Existing genomic surveillance tools face challenges with redundant databases, delaying subtype identification and obscuring reassortment dynamics. K-FluDB, a novel k-mer-based database, addresses these issues by enhancing subtype identification, capturing genomic diversity, and assisting in the detection of reassortment events critical for understanding viral evolution and improving outbreak proactive measures.

Results

K-FluDB provides a comprehensive pangenome for Influenza A, including complete and subtype-specific subsequences from 50 subtype combinations across all 18 hemagglutinin (HA) and 11 neuraminidase (NA) subtypes. Achieving 99.64% compression, K-FluDB eliminates redundancy while preserving essential information. Validation with real-world datasets showed high recovery indices (up to 96.24%) and correct subtype prediction ratios (exceeding 99% for HA and NA). K-FluDB also assists in the detection of reassortment events.

Availability and implementation

Three versions of K-FluDB, optimized for read lengths of 75, 150, and 300 nucleotides, are freely available at [https://zenodo.org/records/17203072](https://zenodo.org/records/17203072), and the source code is available at [https://github.com/usjunco/pangen](https://github.com/usjunco/pangen).

![](/images/Screenshot%20from%202026-04-07%2023-40-59.png)
