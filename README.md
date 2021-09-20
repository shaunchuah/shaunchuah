# Introduction

- 👋 Hi, I’m @shaunchuah, clinical research fellow in gastroenterology.
- 👀 I’m interested in inflammatory bowel diseases, bioinformatics and technology in general.
- 📫 How to reach me: cchuah@ed.ac.uk
- Blog here: https://shaunchuah.github.io/

## Technologies

### Frontend

- HTML
- CSS (Frameworks - bootstrap, tailwind)
- JavaScript (Frameworks - next.js/vue.js/alpine.js)

### Backend

- Django
- Django-Rest-Framework
- PostgreSQL
- Nginx
- Redis

### DevOps

- Docker
- GitHub Actions (CI/CD)
- Managing existing cloud deployments on DigitalOcean, AWS, Azure, Vercel

### Bioinformatics

- Pipeline orchestration (Nextflow, Snakemake)
- QC Tools (FastQC, MultiQC)
- Alignment Tools (bowtie2, minimap2)
- Metagenomics (kraken2, metaphlan)

### Data Analysis

- Python (numpy, pandas, matplotlib, seaborn)
- R (ggplot2, phyloseq)

## Projects

### MUSIC Study

Current research looking at the role of mitochondrial damage-associated molecular patterns in patients with inflammatory bowel disease. Check it out here: https://www.musicstudy.uk

### SampleTrek Web Application

Open Source Repo here: https://github.com/shaunchuah/musicsamples 

Flexible sample tracking for researchers - SAAS available here: https://sampletrek.com/ Documentations: https://docs.sampletrek.com/

Bring your own barcode labels and this will provide the backend to allow multi-user, multi-site collaboration.

Potentially could be developed into a fully integrated customised lab workflow by integrating barcode printers with a raspberry pi/webapi.

### Nextflow Bioinformatics Pipeline for cfDNA Analyses

Bioinformatics pipeline for local development/Azure cloud execution here: https://github.com/shaunchuah/cfdna_nextflow/

Tutorial on how to set up your own Azure cloud supercomputer: [Link here](https://shaunchuah.github.io/posts/setting-up-azure-with-nextflow)

### Dockerized Bioinformatic Tools

| Tool                        | Original Repo                                             | Docker Image                                                                    | Docker Build Source                                                                                                            |
|-----------------------------|-------------------------------------------------------------|---------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------|
| SeqKit 2.0.0                | [Original Repo](https://github.com/shenwei356/seqkit)     | [Docker Image](https://hub.docker.com/r/shaunchuah/seqkit)                      | [Build Source](https://github.com/shaunchuah/seqkit_docker)                                                             |
| CpGIScan (as of 6 Sep 2021) | [Original Repo](https://github.com/jianzuoyi/CpGIScan)    | [Docker Image](https://hub.docker.com/r/shaunchuah/cpgiscan)                    | [Build Source](https://github.com/shaunchuah/cpgiscan_docker)                                                           |
| Kraken-Biom v1.0.1          | [Original Repo](https://github.com/smdabdoub/kraken-biom) | [Docker Image](https://hub.docker.com/repository/docker/shaunchuah/kraken_biom) | [Build Source](https://github.com/1-gut/kraken-biom) |
