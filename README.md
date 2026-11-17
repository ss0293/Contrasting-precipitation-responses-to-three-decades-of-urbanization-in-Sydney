# Contrasting precipitation responses to three decades of urbanization in Sydney

This repository is the companion repository for the research paper
*Contrasting precipitation responses to three decades of urbanization in Sydney*.
It is intended to hold the datasets, analysis code, configuration files,
documentation, and manuscript figures required to reproduce the study once
those materials are added.

## Research objective

The study investigates how urban development has affected precipitation across
Greater Sydney over three decades. It uses paired, 1-km Weather Research and
Forecasting (WRF) simulations to compare precipitation under a fixed urban
land-cover baseline with precipitation under year-specific urban development.

## Experimental design

The simulations cover six years: 1995, 2000, 2005, 2010, 2015, and 2020.

- **CNTRL**: uses fixed 1990 urban land cover.
- **DYN**: incorporates urban development for each corresponding simulation
  year.

The paired experiments are intended to isolate the precipitation response
associated with changes in urban land cover. Detailed methods and processing
information will be documented in [`docs/`](docs/) as the project materials are
added.

## Repository structure

```text
data/       Research datasets and data documentation
scripts/    Python analysis and visualisation code
figures/    Main and supplementary manuscript figures
configs/    Configuration files for analysis and processing
docs/       Methodology and reproducibility documentation
```

Each directory contains a README describing the materials intended for that
location. No analysis scripts, datasets, figures, or scientific results are
included in this initial repository structure.

## Data availability

The datasets and analysis scripts will be added later. Until then, the
repository contains only the organisational structure and documentation
placeholders needed to support a reproducible publication workflow. Large
model outputs, including NetCDF files, should be managed according to the
project's eventual data-sharing and archival arrangements rather than committed
directly to the repository.

## Citation

Citation metadata is provided in [`CITATION.cff`](CITATION.cff). Publication
details, including the DOI, will be completed when they become available.

## Reproducibility

Reproducibility notes, processing decisions, and instructions for running the
eventual workflow will be maintained in [`docs/`](docs/). Configuration values
belong in [`configs/`](configs/) so that analysis scripts can remain separate
from project-specific settings.

## Status

This repository is being prepared for the subsequent addition of the actual
research data, Python scripts, and manuscript figures.
