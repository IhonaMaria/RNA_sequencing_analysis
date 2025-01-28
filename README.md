# RNA_sequencing_analysis
This repository contains the report and R code developed in order to analyze the gene expression of mice mammary gland during 3 different development stages: virgin, pregnant and lactating.
It also includes the counts matrix used for the analysis, which contains raw RNA sequencing counts for the different biological samples. The counts matrix was downloaded from:
https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE60450

Moreover, there is an information matrix that matches each sample with the condition (virgin, pregnant or lactating) and the cell type (basal or luminal).

In order to replicate the study, you only need to use Rstudio and download both txt files and Rmarkdown file. 

### Results and conclusions
As a summary, after the sequencing and transcriptomics analysis, it has been found that:

- During the virgin state, the gene expression prioritizes neurogenesis, structural integrity and extracellular matrix maintenance functions.
- In the pregnant state there is a shift towards the upregulation of lipid metabolism, cell proliferation, and tissue remodeling processes to support alveolar formation and milk production. Immune response and angiogenesis are also critical during this stage.
- Finally, during the Lactating state, the mammary gland focuses on high metabolic activity. Since it needs to produce milk, it upregulates genes involved in fatty acid metabolism, lipid transport, etc while downregulating other structural processes that are less critical in this stage.

Please refer to the report for detailed information and reasoning, and feel free to check on the Rmarkdown file for the data that supports these statements.
