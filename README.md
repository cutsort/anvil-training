
# Training Material for <img src="https://anvilproject.org/static/logo-f572a5fcc603d88700dd44bed44b8830.png" height=35>

This repository contains material to help users migrate their genomic analysis workflows to the [AnVIL](https://anvilproject.org) cloud platform.

## Tutorials

| Analysis     | Inputs                 | Outputs      | Features                           |
|--------------|------------------------|--------------|------------------------------------|
| [GWAS](GWAS) | Local .csv, Cloud .vcf | Top variants | Terra, Dockstore, Jupyter, RStudio |
| GATK         | Local .fastq           | .vcf         | Terra, Dockstore                   |
| scRNA-seq    |                        |              |                                    |

## Technology Overview

- Terra
	- [Running Workflows, Getting Data, Interactive Analysis w/ Jupyter Notebooks](https://drive.google.com/file/d/1wmyeUzC50ko76pJ1oyQmJSEpzjfTGbDP)
	- [Architecture and Design Overview](https://docs.google.com/presentation/d/17B7122itLyn3q0Xp2fMQX7wnTeTozeCvLNVARFDXdqw)
- Dockstore
	- [Intro to Dockstore, Brief Developer Details](https://docs.google.com/presentation/d/1unq_zyd_1u_kEsYKABVMuaIYMjJ0soFTVLcOtD17hlg)
- Gen3
	- [User Perspective, Technical Overview](https://docs.google.com/presentation/d/11c7gKEfOZuu6TCWCDroHgNiVgjP7oIEh-NofRAzsCKw)

## Dockstore Workflows

- [GENESIS GWAS](https://dockstore.org/workflows/github.com/AnalysisCommons/genesis_wdl/genesis_GWAS)
- [GATK collection](https://dockstore.org/organizations/BroadInstitute/collections/GATKWorkflows)
- [BWA align by TOPMed](https://dockstore.org/organizations/bdcatalyst/collections/TOPMedworkflows)
- [10x Genomics scRNA-seq by Human Cell Atlas](https://dockstore.org/workflows/github.com/HumanCellAtlas/skylab/Optimus)

## AnVIL Workspaces

- [ASHG 2019 GWAS Tutorial](https://anvil.terra.bio/#workspaces/amp-t2d-op/2019_ASHG_Reproducible_GWAS-V2)
- [GWAS Tutorial in NHLBI's BioData Catalyst](https://anvil.terra.bio/#workspaces/biodata-catalyst/BioData%20Catalyst%20GWAS%201000%20Genomes%20Tutorial)
- [Bioconductor using Jupyter Notebooks](https://anvil.terra.bio/#workspaces/help-gatk/Bioconductor)
- [COVID-19 scRNA-seq](https://anvil.terra.bio/#workspaces/kco-incubator/COVID-19_cross_tissue_analysis)
- [Human Cell Atlas Optimus Pipeline for 10x Genomics scRNA-seq](https://anvil.terra.bio/#workspaces/featured-workspaces-hca/HCA_Optimus_Pipeline)

## Workshop Guidance

- [Terra in the classroom](https://docs.google.com/presentation/d/1AvEt6UIIx-G5eTe4hlfkGOYsUcSQrKx8ySlnnfg7XH8)

## References

- [Getting Started on Terra](https://support.terra.bio/hc/en-us/categories/360002177552)
- [Terra Documentation](https://support.terra.bio/hc/en-us/categories/360001399872)
- [Genomics in the Cloud](https://www.oreilly.com/library/view/genomics-in-the/9781491975183/) O'Connor and Van der Auwera 2020 O'Reilly
