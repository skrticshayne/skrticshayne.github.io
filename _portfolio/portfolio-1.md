---
title: "COSMIC database Pipeline"
excerpt: |
  Developed a Python Pipeline to easily sort, visualize, and transform cancer data
  <br/>
  <img src="/images/cosmic.png" alt="COSMIC" width="500" height="300">
collection: portfolio

---

This program provides a comprehensive tool for analyzing and visualizing data from the COSMIC Database. It efficiently parses downloaded data to generate insights on various metrics such as histology, age versus frequency, primary site and age correlations, amino acid mutation types, and the frequency of coding and noncoding mutations. It facilitates data visualization through integration with the cBioPortal Mutation Mapper and supports analysis with CRAVAT for VEST, CHASM+, and FATHMM scores.

The user interface includes a script that processes Cravat output to create inputs for the cBioPortal Mutation Mapper. This includes identifying significant missense mutations and generating files necessary for FOLDX molecular modeling. Additionally, the program offers a script for conducting Chi-Square Analysis on functional versus nonfunctional domains of genes, focusing on disruptive and nondisruptive regions.

Moreover, it features a script for modeling significant mutations, as determined by CRAVAT, on protein structures (PDB files). It calculates ΔΔG values for missense mutations and generates updated structural PDBs, providing a holistic view of the mutation impacts on protein function and structure. This suite of tools is designed to enhance the understanding of genetic mutations and their implications, streamlining the process from data parsing to advanced molecular modeling.
