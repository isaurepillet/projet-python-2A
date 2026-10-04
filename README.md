# Rent Control and Housing Prices — Policy Evaluation

**ENSAE Paris — second-year Python project, November 2024–January 2025**

This project was conducted by **Camille Frouard, Caroline Lebrun and Isaure Pillet**. It studies whether the introduction of **rent control in Paris** affected residential property purchase prices.

## Research question

Rent control directly regulates rents, but it may also affect incentives and valuations in the broader housing market. We study whether purchase-price dynamics changed in Parisian areas subject to rent control relative to nearby municipalities where the policy did not apply.

The analysis focuses on two geographic comparisons:

- western Paris (16th and 17th arrondissements) versus nearby municipalities including Levallois-Perret, Boulogne-Billancourt, Clichy and Neuilly-sur-Seine;
- southern Paris (13th, 14th and 15th arrondissements) versus Issy-les-Moulineaux, Malakoff, Montrouge and Vanves.

## Empirical strategy

We use a **Difference-in-Differences (DiD)** framework around the introduction of rent control in Paris on **1 July 2019**. Parisian areas form the treated group and nearby municipalities provide comparison groups.

The outcome of interest is the residential **purchase price per square metre**. Socio-economic characteristics are added as controls using INSEE data.

## Data

The project combines:

- **DVF / DVF+ property-transaction data**, containing information on real-estate transactions and property characteristics;
- **INSEE Filosofi and census data at IRIS level**, used to construct socio-economic controls.

A substantial part of the project involved understanding the different French property-data sources, harmonising geographic information and merging transaction data with INSEE indicators.

## Repository structure

- **`main.ipynb`** — main analysis, from data preparation to the Difference-in-Differences estimation;
- **`functions.py`** — reusable functions used by the analysis;
- **`data/`** — project data and intermediate files;
- **`liste variables DVF`** and **`liste variables bases Insee`** — variable documentation.

## Tools and methods

Python · pandas · Jupyter · data cleaning · geographic matching · Difference-in-Differences · policy evaluation

## Collaboration

This repository is a fork of the original collaborative project. The original authorship is preserved here and in the repository history.
