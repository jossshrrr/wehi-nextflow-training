# WEHI Nextflow Training

## Setup
1. Clone this repostiory to your home directory from vc7-shared
    ```
    cd ~
    git clone https://github.com/jemunro/wehi-nextflow-training.git
    ```
2. Create a run directory on /vast/
    ```
    mkdir -p /vast/scratch/users/$USER/nf-training-run
    ```
3. Change to the run directory
    ```
    cd /vast/scratch/users/$USER/nf-training-run
    ```
4. Load the nextflow module
    ```
    module load nextflow/22.04.5
    ```
5. Join the VSCode live share in your browser

## [Module 1: Hello World](module_1/README.md)
A brief introduction to the Nextflow language

## [Module 2: Nextflow Concepts](module_2/README.md)
Core concepts for developing Nextflow workflows

## [Module 3: NGS Variant Calling Pipeline](module_3/README.md)
An example pipeline calling SARS-Cov-2 variants using bwa, samtools, bcftools and then visualising with R


## Additional Resources
* [Official Nextflow documentaion](https://www.nextflow.io/docs/latest/basic.html)
* [Official Nextflow Slack](https://www.nextflow.io/slack-invite.html)
* [nf-core](https://nf-co.re/) - community pipelines
* [nf-core Slack](https://nf-co.re/join/slack)
* [Introduction to Bioinformatics workflows with Nextflow and nf-core](https://carpentries-incubator.github.io/workflows-nextflow/index.html) - comprehensive Nextflow tutorial using DSL2
* [Groovy Web Console](https://groovyconsole.appspot.com/) - useful for testing Groovy/Java code fragments