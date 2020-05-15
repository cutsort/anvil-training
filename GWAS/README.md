
# Zero to GWAS with AnVIL

This tutorial demonstrates how to run a GWAS analysis on [AnVIL](https://anvilproject.org) leveraging material originally created for a [2019 ASHG workshop](https://anvil.terra.bio/#workspaces/amp-t2d-op/2019_ASHG_Reproducible_GWAS-V2).

<img src="https://anvilproject.org/static/logo-f572a5fcc603d88700dd44bed44b8830.png" height=30><img src="https://theme.zdassets.com/theme_assets/2378360/7b2886b47ee19caff6ddae04c4cb4f4fbcb24448.png" height=30> <img src="https://pbs.twimg.com/profile_images/825416462747656192/CWnYu9Fe_400x400.jpg" height=30> <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/3/38/Jupyter_logo.svg/1280px-Jupyter_logo.svg.png" height=30> <img src="https://docs.dockstore.org/en/develop/_images/wdl.png" height=30><img src="https://cromwell.readthedocs.io/en/stable/jamie_the_cromwell_pig.png" height=30><img src="https://d33wubrfki0l68.cloudfront.net/62bcc8535a06077094ca3c29c383e37ad7334311/a263f/assets/img/logo.svg" height=30>

## Learning Goals

- Create a [workspace](https://www.youtube.com/watch?v=ONc1Wf7rEuw) on Terra
- Import a workflow from [Dockstore](https://support.terra.bio/hc/en-us/articles/360038137292)
- Explore data interactively using [Jupyter](https://www.youtube.com/watch?v=DbakAsk4-5c)
- Run a [batch analysis](https://support.terra.bio/hc/en-us/articles/360036379771) using WDL
- Explore data interactively using [RStudio](https://github.com/anvilproject/anvil-docker/tree/master/anvil-rstudio-bioconductor)

## Required Materials

1. Billing account -- You must have a [Billing Project](https://support.terra.bio/hc/en-us/articles/360026182251) to complete this tutorial.
2. Sample data and configuration files
    - [sample.tsv](https://drive.google.com/uc?id=1lb3FyEla-zWYois5RUbjwgBkl9m_Hp8S) - Sample data [2504 x 14]
    - [sample_set.tsv](https://drive.google.com/uc?id=1KkzGoqZtovY1k3wXvwgJvL64rz-BwOLE) - Input parameters [1 x 5]
    - [my_phenotypes.csv](https://drive.google.com/uc?id=1DIYoSg3ibq_O8ANGLKws3g8spg1-RCJu) - Sample data w/ first two principal components 2504 x 16
    - [gds.tsv](https://drive.google.com/uc?id=1lVH1bMhW04qX19TSEToYkGSE88QARc39) - GDS file locations [1 x 22]

## Sections

0. Introduction [[movie](https://drive.google.com/uc?id=1dO4xsI6FDC7VMmGIs3APvP4BmxgZEAAd)][[slides](https://docs.google.com/presentation/d/1eOk8Rq7gJP3aCheOZvBRH4fxxF9q9LbH1Ukb034hEv8)]
1. Create workspace
1. Import workflow
1. Upload sample data
1. Explore phenotype distributions
1. Prepare input parameters
1. Point to GDS / VCF files
1. Configure workflow
1. Run workflow
1. Explore top variants [[movie](https://drive.google.com/uc?id=1GdJeq2lrlQv0Ba44q3E74_dPdmdkeJO5)][[slides](https://docs.google.com/presentation/d/1ezmW_hRlq9gcQO3DQcTtOCvFsuZHbxiXxOre3955LJI)]
    - `us.gcr.io/anvil-gcr-public/anvil-rstudio-bioconductor:0.0.4`

