# EWAS tool development / Training / Elixir-CNV community

Dr Krzysztof Poterlowicz <!-- .element: class="whitetext" -->

---

#### Aims

- EWAS tool development
- Training in Epigenetics
- Elixir-CNV community

Note:
this is how you add speaker notes. Can view these in presentation mode by pressing "S"

---

#### EWAS tool development

@size[0.5em](The aim of our project was to develop a population-wide DNA methylation pipeline that is easy to apply and compatible with routine clinical and biological use.)

---?image=EWAS_Elixir_CNV/images/epigenetics.jpg&position=bottom

#### @size[0.6em](Epigenome-wide Association Studies)


---

@size[0.7em](Epigenome-wide association studies - EWAS analyse genome-wide activity of epigenetic marks in cohorts of different individuals to find associations between epigenetic variation and phenotype. With its high accuracy and low input DNA requirements, the llumina 450k Methylation Assay has became one of the most comprehensive EWAS study solutions. Unfortunately, analysis of the existing 450k data requires considerable programming knowledge and experience as well as high-performance computational hardware.)

---

#### Galaxy server in Centre for Skin Sciences
@ul
- More than 200 bioinformatics tools integrated allowing transcriptomics, epigenetics analysis and large scale data visualization.
- Available to CSS researchers as a web-based platform.
- Biomedical researchers without programming experience can easily apply tools and workflows to perform transcriptomics, genomics, epigenetics analysis.
@ulend

---

#### Research Software Development
@ul
- Determining  genetic and non-genetic factors in disease aetiology is one of the principal challenges in clinical and biomedical research.

- Our recently developed suite provides a group of integrated tools that combine analytical methods to analysis epigenetics data into a range of handy easy to use pipelines.
@ulend

---?image=EWAS_Elixir_CNV/images/workflow.png

---

#### Training in Epigenetics

@size[0.7em](We have also provided training sessions and interactive tours for user self-learning. The training materials are freely accessible at the Galaxy project Github repository. Such training and tours guide users through an entire analysis.)

---?image=EWAS_Elixir_CNV/images/load.png

---

#### EWAS - Applications

@size[0.5em](With the rapidly increasing volume of epigenetics data available, computer-based analysis of heritable changes in gene expression becomes more and more feasible. Many genome-wide epigenetics studies have focused on generation of the data, however data interpretation is a challenge now. Risk evaluation, disease management and novel therapeutic development are prompting researchers to find novel bioinformatic frameworks and approaches.  In this regard we propose a user friendly tool suite available via Galaxy platform 'EWAS-Galaxy'. This tools suite allows life scientist to run complex epigenetics analyse.)

---

#### Epigenetics Data Analysis

@ul
The analysis combines 6 main steps:
- 1 Raw intensity data loading .idat files
- 2 Preprocessing and optional normalization
- 3 Quality assessment and control step
- 4 Single nucleotide polymorphism finding and removal
- 5 Differentially methylated positions and regions finding with respect to a phenotype covariate
- 6 Functional annotation and graphical representation
@ulend

---

#### Elixir-CNV Community
@ul
The aims of the Community, as set out in its application, are to:

- Define optimal CNV detection pipelines

- Create reference datasets

- Define a data exchange format to allow comparison of NGS data

- Develop and provide access to innovative bioinformatics tools to target potential disease-causing genes
@ulend
---

####  CNV Detection Pipelines

Multiples initiatives have been made to produce optimal pipelines to detect CNV using micro-array, WES or WGS data. To reach this objective, three tasks are proposed:
@ul
- will establish the list of available pipelines/software as well as partners

- will benchmark systems using provided datasets 

- will optimize the selected generated pipelines 
@ulend

---

####  Creation of Innovative Tools
@ul
- develop specific bioinformatics tools to select candidate genes localized in the CNV region by combining genes' annotations and patients' phenotype.

- define CNV annotations 

- develop a specific pipeline to interpret duplications as tandem
@ulend
---

####  FAIRification of h-CNV services and datasets

# Findable Accessible Interoperable Reusable

---
####  Alignment with ELIXIR platforms
@size[0.5em](The h-CNV communities objectives have many links to ELIXIR platforms as illustrated below:)

image=EWAS_Elixir_CNV/images/elixir.png&size=50%
---
#### Summary
@size[0.5em](We have develop a tool suite for population epigenetics analysis. Researchers can easily investigate methylation changes in multiple human phenotype cases i.e. weight, high, age. We encourage YOU to explore accessibility, reproducibility and serviceability of EWAS suite and pipelines. In addition growing interest for epigenomics and genomics including CNV detection and interpretation in human diseases will ensure the global recognition and expansion of the community and will trigger many interactions both for other ELIXIR Communities as the Marine Metagenomics and Plant Sciences and industry.) 
