## UCSC Cell Browser Activity

## Assigned Gene and Disease

| Information | Result |
|---|---|
| Assigned gene | TP53 |
| Associated disease | Li-Fraumeni syndrome |

## Organ/Tissue Choice and Dataset Information

**Dataset Name:** Tabula Sapiens — Bone Marrow

**Collection:** Tabula Sapiens

**Organ/Tissue:** Bone marrow

**Dataset ID:** tabula-sapiens/by-organ/bone-marrow

**Dataset URL:** https://tabula-sapiens.cells.ucsc.edu 

**Reference:** Speir et al., 2021 

## Reason for Selecting the Dataset

I selected the Bone Marrow dataset from Tabula Sapiens to investigate TP53 gene expression in bone marrow cells. I will explore its possible relationship with my assigned disease, Li-Fraumeni syndrome.

## Screenshot 1 — Selected Dataset
<img width="1168" height="2038" alt="IMG_3964" src="https://github.com/user-attachments/assets/652dca9f-00c7-4fd4-a7d7-0b60eb4f8d1e" />

## Understanding the Cell Map

**a. What type of visualization is being shown?**

The Tabula Sapiens Bone Marrow dataset uses a UMAP visualization.

**b. What does one dot represent?**

Each dot represents one measured cell in the dataset.

**c. What do the clusters represent in this particular dataset?**

The clusters represent groups of bone marrow cells with similar molecular profiles. The different clusters are labeled according to their cell types.

**d. List at least three cell-type or cluster labels
visible in the dataset.**

1. CD24 neutrophil
2. CD4-positive, alpha-beta T cell
3. CD8-positive, alpha-beta T cell

## Assigned Gene Expression

**a. Assigned gene symbol** TP53

**b. Dataset used** Tabula Sapiens — Bone Marrow

**c. Is expression widespread, restricted, or low/undetected?**

TP53 expression is detectable across several cell clusters, but its intensity varies. Many cells show low or undetected expression, while some clusters contain cells with stronger expression.

**d. Which clusters appear to contain cells with stronger expression?**

Stronger expression signals are visible in parts of the myeloid progenitor, erythroid progenitor, and granulocyte clusters.

**e. Which clusters appear to contain little or no detectable expression?**

The CD24 neutrophil cluster contains many cells with low or undetected expression. Low expression is also visible in many cells within the T-cell clusters.

### Screenshot 2 — TP53 Gene Expression
<img width="1169" height="2104" alt="IMG_3966" src="https://github.com/user-attachments/assets/a6249aa7-8d7c-48ce-9f4e-8a20df088cb8" />

## Cell Types Expressing TP53

**a. Cell type/cluster with the strongest visible expression**

The myeloid progenitor cluster shows some of the strongest visible TP53 expression signals.

**b. Another cell type/cluster with detectable expression**

TP53 expression is also detectable in the
erythroid progenitor cluster.

**c. Cell type/cluster with relatively low or undetected expression**

The CD24 neutrophil cluster contains many cells with low or undetected TP53 expression.

**d. Is the expression pattern broad or cell-type restricted?**

TP53 expression appears across several cell types, but its intensity varies among clusters. The pattern is relatively broad rather than restricted to a single cell type.

**e. Possible biological explanation for the observed pattern**

Based on the selected Bone Marrow dataset, TP53 expression varies among different cell types. One possible explanation is that these cells have
different biological states or activities, which may influence their gene-expression levels. This is an interpretation of the observed dataset,
not a confirmed explanation.

## Screenshot 3 — Cell Types Expressing TP53
<img width="1169" height="2097" alt="IMG_3965" src="https://github.com/user-attachments/assets/b794242c-301f-4904-92ac-87aca2675695" />

## Select Cells and Examine an Expression Plot

**a. Which cells/cluster did you select?**

I examined the myeloid progenitor cluster using the TP53 expression dot plot and compared it with other bone marrow cell types, particularly CD24 neutrophils. I used the dot-plot alternative because I could not select cells using the rectangle tool.

**b. Does your selected group show higher, lower, or similar expression compared with the comparison cells?**

The myeloid progenitor cluster has a larger TP53 dot than the CD24 neutrophil cluster, indicating that a greater proportion of its cells have detectable TP53 expression.

**c. What does the expression plot add that was not obvious from the UMAP?**

The dot plot allows TP53 expression to be compared across different cell types. Dot size represents the proportion of cells with detectable expression, while dot color represents average expression. This provides additional information beyond the spatial distribution shown in the UMAP.

## Screenshot 4 — TP53 Expression Dot Plot
<img width="1168" height="2062" alt="IMG_3970" src="https://github.com/user-attachments/assets/c3ee0e73-fe85-45e8-a2a8-037652a80089" />

## Explore Marker Genes

**a. Cluster/cell type examined** Myeloid progenitor

**b. Marker gene 1** MAZ

**c. Marker gene 2** PPDPF

**d. Marker gene 3** SMIM10L1

**e. Does TP53 behave like a cell-type marker in this dataset?**

TP53 does not appear to be specific to the myeloid progenitor cluster because its expression is also detectable in other bone marrow cell types. Based on the expression map, TP53 does not appear
to behave like a cell-type-specific marker.

## Screenshot 5 — Myeloid Progenitor Marker Genes
<img width="1169" height="2101" alt="IMG_3971" src="https://github.com/user-attachments/assets/83f58527-7d35-427f-8b9d-6cc508506729" />

## Comparing TP53 With a Marker Gene

**a. Assigned disease gene** TP53

**b. Marker gene** MAZ

**c. Which gene shows a more cell-type-restricted expression pattern?**

Neither gene appears strictly restricted to one cell type. However, MAZ shows more prominent expression in certain clusters, particularly the myeloid and erythroid progenitor clusters.

**d. Which gene appears more broadly expressed?**

Both TP53 and MAZ are detectable across multiple bone marrow cell types. Based on the UMAP images, their relative breadth cannot be determined confidently without comparing expression values.

**e. What does this comparison teach you about the difference between a disease-associated gene and a cell-type marker gene?**

This comparison shows that a disease-associated gene does not necessarily have expression restricted to one cell type. Although MAZ was listed among the myeloid progenitor marker genes, its expression is also visible in other clusters. Therefore, being listed as a marker does not mean a gene is expressed exclusively in that cell type.


## Connecting the Genome Browser and Cell Browser Results

**1. On which chromosome is your assigned gene located?**

TP53 is located on chromosome 17. In my previous UCSC Genome Browser activity, I recorded its genomic coordinates as chr17:7,661,779–7,687,546 on the GRCh38/hg38 assembly. The gene is located on the minus strand.

**2. What disease-associated variant did you examine previously?**

I examined the TP53 variant NC_000017.11:g.7668194C>T, located at chr17:7,668,194 (GRCh38). Its ClinVar Variation ID is 3045221, and its associated condition is TP53-related disorder. ClinVar reports its clinical significance as Likely benign.

**3. In the current Cell Browser dataset, which cell types express the gene?**

In the Tabula Sapiens Bone Marrow dataset, TP53 expression is detectable in several cell types, including myeloid progenitors, erythroid progenitors, and granulocytes. Many CD24 neutrophils show low or undetected expression.

**4. Does the observed cell expression make biological sense based on what you already know about the gene's function or associated disease? Explain in 3–5 sentences.**

The observed expression is consistent with TP53 being a tumor-suppressor gene rather than a gene specific to only one cell type. TP53 expression was detectable across several bone marrow cell populations, although its intensity varied. Some progenitor-cell clusters showed stronger visible expression, while many CD24 neutrophils showed low or undetected expression. These observations suggest that TP53 may have roles in different bone marrow cell types, but the expression map alone cannot establish its specific function in each cell type.

**5. Can this single Cell Browser dataset
prove that the gene causes the disease?
Explain why or why not.**

No. The Cell Browser dataset shows where
TP53 expression is detectable, but it
does not demonstrate that a particular TP53 variant causes Li-Fraumeni syndrome. The variant examined in my previous activity was classified as Likely benign by ClinVar. Additional genetic and functional evidence would be needed to establish whether a particular variant contributes to disease.


## Short Reflection

**1. What did the UCSC Cell Browser show you that the UCSC Genome Browser could not?**

The UCSC Cell Browser showed me how TP53
expression varies among different bone marrow cell types. Unlike the Genome Browser, which showed the gene's location, structure, and variants, the Cell Browser allowed me to observe gene expression in individual cells and compare different cell clusters.

**2. Why can the same gene have different expression levels among different cell types?**

Different cell types have different functions and biological activities. Therefore, they may express the same gene at different levels depending on their cellular needs and biological states.

**3. Why should you be careful when interpreting a gene that shows zero or very low expression in single-cell data?**

Zero or very low expression does not always mean that a gene is completely inactive in a cell. Some gene expression may be too low to detect using single cell measurements, so the results should be interpreted carefully.

**4. Why is it useful to combine information about genomic location, genetic variants, and cell-specific gene expression?**

Combining this information helps us understand where a gene is located, how its structure is organized, and where its expression can be detected. It also allows us to examine genetic variants alongside the cell types in which the gene is expressed. Together, these observations provide a more complete understanding of a disease-associated gene.

**5. What was the most interesting observation you made about your assigned gene?**

The most interesting observation was that TP53 expression was detectable in several bone marrow cell types rather than being restricted to one cluster. I also observed that some myeloid and erythroid progenitor cells showed stronger expression signals, while many CD24 neutrophils showed low or undetected expression.


## References and Links

**UCSC Cell Browser**  
https://cells.ucsc.edu/ 

**Tabula Sapiens — Bone Marrow Dataset**  
https://tabula-sapiens.cells.ucsc.edu 

Dataset ID: `tabula-sapiens/by-organ/bone-marrow` 

**Cell Browser Reference**  
Speir et al. (2021).  
https://academic.oup.com/bioinformatics/article/37/23/4578/6318386 

**UCSC Genome Browser**  
https://genome.ucsc.edu/ 
