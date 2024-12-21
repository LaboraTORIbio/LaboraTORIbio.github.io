---
layout: default
---


<img src="/assets/images/profile_photo_circle2.png" style="float: right; width: 170px;">

Hi! I'm Laura Toribio (a.k.a. **Tori**). I'm a **Bioinformatician** with a **nearly completed PhD** and over 4 years of hands-on experience in analyzing multi-omics biological data. I'm competent in Python, R and shell scripting, continuously enhancing my programming skills. Also hooked on aesthetic **data visualization** and presentation. 

My growing interest for emerging technologies has led me to explore and learn **Data Science**. My aspiration is to merge Bioinformatics and **Machine Learning**, applied to biological processes, to foster progress in healthcare and life sciences.


<br>

## Technical skills

* Python: pandas, numpy, matplotlib, plotly
* Data Science: scikit-learn, TensorFlow, Keras
* Shell scripting: bash, awk, sed
* Containerization: Docker
* Amazon Web Services: AWS Lambda, API Gateway, Elastic Container Registry
* High Performance Computing (HPC)
* R: ggplot2, tidyverse
* Git & Github

<br>



## Projects

{% tabs projects %}

{% tab projects Bioinformatics%}


#### Transcriptomic Analyses

* Developed a standard workflow for RNA-Seq data analysis in **R**, including read count with **featureCounts** and differential expression analysis with **DESeq2**.
* Performed gene set enrichment analysis (GSEA) with **clusterProfiler**.
* Wrote **Shell** (documented in MarkDown files) and **Python** scripts for manipulating/filtering output files used as input in downstream steps of the pipeline.

&nbsp;🔗 [RNA-Seq_1st_dataset](https://github.com/LaboraTORIbio/RNA-Seq_enterobacteria_pOXA-48/blob/main/RNA-Seq_1st_dataset/RNA-Seq_1st_dataset.md)
&nbsp;🔗 [RNA-Seq_DeltaLysR](https://github.com/LaboraTORIbio/RNA-Seq_enterobacteria_pOXA-48/blob/main/RNA-Seq_DeltaLysR/RNA-Seq_2nd_dataset.md)
&nbsp;🔗 [RNA-Seq_experimental_evolution](https://github.com/LaboraTORIbio/RNA-Seq_enterobacteria_pOXA-48/blob/main/RNA-Seq_experimental_evolution/RNA-Seq_experimental_evolution.md)



#### Ancestral Character Reconstruction

* Downloaded and analyzed a large **RefSeq database** of bacterial genomes.
* Constructed large bacterial phylogenies using **IQ-TREE** from genetic markers identified with Hidden Markov Models (**hmmsearch**).
* Performed ancestral character reconstruction with **PastML**.
* Wrote **Shell** (documented in MarkDown files) and **Python** scripts for manipulating/filtering output files used as input in downstream steps of the pipeline.

&nbsp;🔗 [LysR_and_the_mystery_operon](https://github.com/LaboraTORIbio/RNA-Seq_enterobacteria_pOXA-48/blob/main/LysR_and_the_mystery_operon/LysR_and_the_mystery_operon.md)



#### Comparative Genomic Analysis and Phylogenetic Logistic Regression

* Performed diverse comparative genomic analyses to identify genetic traits that could be associated to a certain phenotype, using tools like **MacSyFinder** or **BLAST**.
* Analyzed the potential associations with Fisher's exact tests and phylogenetic logistic regression (**phyloglm**) to account for phylogenetic dependency.
* Wrote **Shell** (documented in MarkDown files) and **Python** scripts for manipulating/filtering output files used as input in downstream steps of the pipeline.

&nbsp;🔗 [Super-sinks](https://github.com/LaboraTORIbio/super-sinks)



#### Variant Calling

* Constructed *de novo* genomic assemblies using **SPAdes**, **Unicycler** and **Flye**.
* Performed diverse analyses of genomic variants using tools like **snippy** and **breseq**.

&nbsp;🔗 [Closing_reference_genomes](https://github.com/LaboraTORIbio/RNA-Seq_enterobacteria_pOXA-48/blob/main/Genome_assemblies/closing_reference_genomes.md)
&nbsp;🔗 [Within-patient_evolution](https://github.com/LaboraTORIbio/within_patient_evolution/blob/main/within_patient_evolution.md)
&nbsp;🔗 [CRISPR_cured_pOXA-48](https://github.com/LaboraTORIbio/CRISPR_cured_pOXA-48/blob/main/CRISPR_cured_pOXA-48.md)


{% endtab %}


{% tab projects Data Science %}



#### Life Expectancy Prediction

* Deployed a robust regression model to predict the life expectancy of a population, achieving a high model accuracy, with an average prediction error of 2.8 years.
* Performed exploratory data analysis and preprocessing (feature selection, missing data imputation with MICE, data transformation, etc) of the WHO's Life Expectancy dataset, improving the dataset quality.
* Trained and simultaneously fine-tuned different ML models (linear regressions, decision trees and ensemble methods), using scikit-learn, to predict the life expectancy of a given country, accounting for the time-series nature of the dataset.
* Model containerization and deployment with Docker and Flask.

&nbsp;🔗 [Life Expectancy Prediction](https://github.com/LaboraTORIbio/life_expectancy_prediction)

<img src="/assets/images/proj_lep.png" style="float: right; width: 170px;">



#### Breast Cancer Image Classifier

* Developed a Convolutional Neural Network model to classify breast ultrasound images into normal, benign and malignant, achieving an overall 85% accuracy.
* Performed transfer learning using TensorFlow and Keras, training a Neural Network on top of the ResNet50 architecture, with subsequent fine-tuning of the outer convolution layers to improve model accuracy.
* Deployed the model as a web service through AWS Lambda and API Gateway, with the containerized model (Docker) uploaded in a AWS Elastic Container Registry.

&nbsp;🔗 [Breast Cancer Classifier](https://github.com/LaboraTORIbio/breast_cancer_classifier)

<img src="/assets/images/proj_bcc.png" style="float: right; width: 170px;">



#### Generalized additive models

* Constructed two **GAMs** with the R package **mgcv** to assess the effect of the concentration of two treatments in the growth (measured as AUC of growth curves) of two bacterial strains, including interaction terms for the type of treatment and the genotype.

&nbsp;🔗 [GAM](https://github.com/LaboraTORIbio/RNA-Seq_enterobacteria_pOXA-48/blob/main/EDA_Stats_Figs/GAM.R)



#### Dimensionality reduction and hierarchical clustering

* Performed **PCA**, **t-SNE** and **hierarchical clustering** in **R** to identify clusters of bacterial strains with similar transcriptional profiles.

&nbsp;🔗 [Dimensionality reduction and hierarchical clustering](https://github.com/LaboraTORIbio/RNA-Seq_enterobacteria_pOXA-48/blob/main/EDA_Stats_Figs/EDA_Stats_Figs.md#dimensionality-reduction-and-hierarchical-clustering)


{% endtab %}

{% endtabs %}

<br>



## Experience

**Bioinformatics Scientist** @ Centro Nacional de Biotecnología-CSIC, Madrid, Spain (Feb. 2021 - Currently)

**Visiting Scientist** @ Institut Pasteur, Paris, France (Feb. 2022 - Mar. 2022)

**Junior Bioinformatics Scientist** @ IRYCIS, Madrid, Spain (Oct. 2019 - Feb. 2021)

**Research Assistant** @ Ikan Biotech, Noain, Spain (Nov. 2018 - Jun. 2019)

**Junior Research Scientist** @ Centro de Biología Molecular Severo Ochoa-CSIC, Madrid, Spain (Feb. 2018 - Sept. 2018)

**Junior Clinical Scientist** @ Hospital Universitario de Guadalajara, Guadalajara, Spain (Feb. 2017 - Jun. 2017)


<br>



## Education

**PhD in Molecular Biosciences - Bioinformatics and Systems Biology** @ Universidad Autónoma de Madrid, Spain (2020 - Currently)

**MSc in Advanced Bioinformatic Analysis - NGS Data Analysis and Data Science** @ Universidad Pablo de Olavide de Sevilla, Spain (2018 - 2021)

**MSc in Biotechnology** @ Universidad Autónoma de Madrid, Spain (2017 - 2018)

**BSc in Biology** @ Universidad de Alcalá de Henares, Spain (2012 - 2017)

<br>



## Publications

* Sastre-Dominguez J, DelaFuente J, **Toribio-Celestino L**, Herencias C, Herrador-Gomez P, Costas C, Hernandez-Garcia M, Canton R, Rodriguez-Beltran J, Santos-Lopez A, San Millan A. (2024) Plasmid-encoded insertion sequences promote rapid adaptation in clinical enterobacteria. __*Nat Ecol Evol*__. doi: [10.1038/s41559-024-02523-4](https://doi.org/10.1038/s41559-024-02523-4).
* Blanco P, Hipólito A\*, García-Pastor L\*, Trigo da Roza F, **Toribio-Celestino L**, Ortega AC, Vergara E, San Millán Á, Escudero JA. (2024) Identification of promoter activity in gene-less cassettes from Vibrionaceae superintegrons. __*Nucleic Acids Res*__. 52(6):2961-2976. doi: [10.1093/nar/gkad1252](https://academic.oup.com/nar/article/52/6/2961/7517494).
* **Toribio-Celestino L\***, Alonso-Del Valle A\*, Quirant A, Pi CT, DelaFuente J, Canton R, Rocha EPC, Ubeda C, Peña-Miller R, San Millan A. (2023) Antimicrobial resistance level and conjugation permissiveness shape plasmid distribution in clinical enterobacteria. __*Proc Natl Acad Sci USA*__. 120(51):e2314135120. doi: [10.1073/pnas.2314135120](https://www.pnas.org/doi/abs/10.1073/pnas.2314135120).
* **Toribio-Celestino L\***, Fernández-Calvet A\*, Alonso-Del Valle A, Sastre-Dominguez J, Valdes-Chiara P, San Millan A, DelaFuente J. (2023) The distribution of fitness effects of plasmid pOXA-48 in clinical enterobacteria. __*Microbiology*__. 169(7):001369. doi: [10.1099/mic.0.001369](https://www.microbiologyresearch.org/content/journal/micro/10.1099/mic.0.001369).
* DelaFuente J, **Toribio-Celestino L**, Santos-Lopez A, León-Sampedro R, Alonso-Del Valle A, Costas C, Hernández-García M, Cui L, Rodríguez-Beltrán J, Bikard D, Cantón R, San Millan A. (2022) Within-patient evolution of plasmid-mediated antimicrobial resistance. __*Nat Ecol Evol*__. 6(12):1980-1991. doi: [10.1038/s41559-022-01908-7](https://www.nature.com/articles/s41559-022-01908-7).

\* Contributed equally