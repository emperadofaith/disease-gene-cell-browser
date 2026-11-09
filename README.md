# UCSC Cell Browser Activity

# Part A

## Assigned Gene and Associated Disease

**Gene:** BRCA2 (BRCA2 DNA Repair Associated)

**Associated Disease:** Hereditary Breast and Ovarian Cancer (HBOC) syndrome

**Gene Description:** BRCA2 is a tumor suppressor gene located on chromosome 13 that encodes a protein involved in repairing damaged DNA through homologous recombination. Pathogenic variants in BRCA2 can impair DNA repair and increase the risk of developing certain cancers, particularly breast and ovarian cancer.

**Objective:** To examine BRCA2 expression across different cell types using the UCSC Cell Browser and relate its expression pattern to its biological function and disease association.

# Part B

## Dataset information

| **Information** | **Details** |
|-----------------|-------------|
| **Dataset** | Tabula Sapiens – By Organ – Mammary Gland |
| **Organ/Tissue** | Human mammary gland (breast) |
| **Assigned Gene** | BRCA2 |
| **Associated Disease** | Hereditary Breast and Ovarian Cancer (HBOC) |
| **Cells Loaded** | 11,375 |

The Tabula Sapiens Mammary Gland dataset was selected because BRCA2 is associated with hereditary breast and ovarian cancer syndrome. This dataset contains human breast epithelial cells and other cell types, allowing the examination of BRCA2 expression in a biologically relevant tissue.

**Screenshot 1.**
<img width="1920" height="1032" alt="image" src="https://github.com/user-attachments/assets/c238ca88-50cf-440d-9f6a-03da34794eb9" />

# Part C

## Understanding the cell map

**Visualization Type:** UMAP (Uniform Manifold Approximation and Projection)

**Dataset:** Tabula Sapiens – By Organ – Mammary Gland

### Cell Map Interpretation

The UMAP visualization displays 11,375 individual cells from the human mammary gland. Each dot represents a single cell, while clusters represent groups of cells with similar gene-expression profiles. The clusters correspond to different cell types, including luminal epithelial cells, basal cells, and breast fibroblasts. The UMAP positions reflect similarities in gene expression rather than actual physical locations within the tissue.

## Identified Cell Types

| Cell Type | Description |
|---|---|
| Luminal epithelial cells | Cells that line the mammary ducts and contribute to glandular functions. |
| Basal cells | Cells associated with the basal layer of the mammary epithelium that provide structural and functional support. |
| Breast fibroblasts | Connective tissue cells involved in maintaining the extracellular matrix and supporting breast tissue structure. |

# Part D

## Gene Expression Analysis

**Assigned Gene:** BRCA2
**Dataset**: Tabula Sapiens – By Organ – Mammary Gland
**Total Cells:** 11,375

BRCA2 showed low overall expression across the mammary gland dataset, with 97.1% of cells having zero recorded expression and approximately 2.9% showing detectable expression. Positive signals were scattered across several clusters, including luminal epithelial cells, T cells, and breast fibroblasts. Basal cells and several smaller clusters showed little detectable expression. These findings suggest that BRCA2 expression was sparse rather than strongly restricted to a single cell type in this dataset.

**Screenshot 2. BRCA2 Expression Map**
<img width="1920" height="1027" alt="image" src="https://github.com/user-attachments/assets/eb8376a8-4ed8-43d2-91e6-d7cd7cdcf5e7" />

# Part E. 

## Cell Types Expressing BRCA2

BRCA2 showed generally low expression across the mammary gland cell types. Vein endothelial cells displayed the highest apparent average expression, while luminal epithelial cells also showed detectable expression. Basal cells exhibited relatively low expression. Overall, BRCA2 expression was sparse across multiple cell types rather than strongly restricted to a particular cluster.

## Biological Interpretation

BRCA2 is involved in DNA repair through homologous recombination, a process important for maintaining genomic stability. Its detectable expression across different mammary gland cell types is consistent with its general role in DNA maintenance. The low detection frequency may reflect differences in cellular activity, gene regulation, and limitations of single-cell RNA sequencing.

**Screenshot 3. Gene expression map**
<img width="1920" height="1026" alt="image" src="https://github.com/user-attachments/assets/b95986c3-d155-4415-b818-3332aec2f7ee" />

# Part F. 

## BRCA2 Gene Expression Plot

**Gene Analyzed:** BRCA2
**Comparison Groups:** Mammary gland cell types
**Plot Type:** Dot plot

## Expression Plot Interpretation

The dot plot showed low BRCA2 expression across the examined cell types, with small dots indicating that only a limited proportion of cells had detectable expression. Vein endothelial cells showed relatively higher average expression, while basal cells showed lower expression. Unlike the UMAP visualization, the dot plot allowed direct comparison of average gene expression and the proportion of expressing cells across different cell types.

**Scrennshot 4. BRCA2 expression dot plot**
<img width="836" height="914" alt="image" src="https://github.com/user-attachments/assets/47cd976e-ee94-4448-8003-3fd7b4d94697" />

# Part G.

## Cluster Marker Genes

**Selected Cluster:** Luminal epithelial cells of the mammary gland

## Identified Marker Genes

| Marker Gene | Z-score |
|---|---:|
| ADIRF | 46.7823 |
| AC010329 | 27.5899 |
| AC024293 | 24.2532 |

## Interpretation

The marker-gene analysis identified ADIRF, AC010329, and AC024293 as genes associated with the luminal epithelial cell cluster. Their positive z-scores indicate statistical association with this cell type. In contrast, BRCA2 showed low and scattered expression across multiple cell types, suggesting that it does not function as a distinctive cell-type marker in this dataset.

**Screenshot 5. marker gene visualization**
<img width="1725" height="881" alt="image" src="https://github.com/user-attachments/assets/9083c452-616a-42ec-8846-00fe516fb18b" />

# Part H.

## Comparison of BRCA2 and ADIRF

**Assigned Disease Gene:** BRCA2  
**Selected Marker Gene:** ADIRF  
**Dataset:** Tabula Sapiens – By Organ – Mammary Gland

### Gene Expression Comparison

| Parameter | BRCA2 | ADIRF |
|---|---|---|
| Biological Role | DNA repair and genomic stability | Adipogenesis-related gene |
| Cells With Detectable Expression | 2.9% | 53.2% |
| Expression Pattern | Low and scattered | Broader and stronger |
| Cell-Type Specificity | No clear cell-type restriction | Enriched in particular cell types |

### Interpretation

ADIRF showed stronger and more widespread detectable expression than BRCA2, particularly in vascular-associated smooth muscle cells, luminal epithelial cells, and vein endothelial cells. Although ADIRF was detected across multiple cell types, its expression was more strongly enriched in certain populations. BRCA2 showed sparse expression without clear cell-type specificity. This comparison demonstrates that a disease-associated gene can perform an important biological function without being highly expressed or serving as a cell-type marker.

# Part I.

## Connection to UCSC Genome Browser and ClinVar

### Genomic and Disease Information

| Parameter | Details |
|---|---|
| Assigned Gene | BRCA2 |
| Chromosome | 13 |
| Cytogenetic Location | 13q13.1 |
| Disease-Associated Variant | NC_000013.11:g.32315358_32316294del |
| ClinVar Variation ID | 873424 |
| Variant Type | 937-bp deletion |
| Clinical Classification | Pathogenic |
| Associated Disease | Hereditary Breast and Ovarian Cancer (HBOC) syndrome |

### Gene-to-Cell Connection

**Chromosome Location → Gene Structure → Disease-Associated Variant → Gene Expression → Cell Type/Tissue**

BRCA2 is located on chromosome 13q13.1 and contains coding regions that encode a protein involved in DNA repair through homologous recombination. The previously examined variant, NC_000013.11:g.32315358_32316294del, is a 937-bp deletion classified as pathogenic in ClinVar.

In the Tabula Sapiens Mammary Gland dataset, BRCA2 showed low and scattered detectable expression across several cell types, including luminal epithelial cells, T cells, and breast fibroblasts.

### Biological Interpretation

The observed expression is biologically consistent with BRCA2's role in maintaining genomic stability through DNA repair. Its detection in mammary gland cells is relevant because pathogenic BRCA2 variants are associated with increased breast cancer susceptibility. Although expression was low, BRCA2 may still perform essential cellular functions, since transcript detection does not directly measure protein activity.

### Limitations

A single-cell expression dataset cannot prove that BRCA2 causes hereditary breast and ovarian cancer. It only shows where BRCA2 transcripts were detected in the sampled tissue. Establishing a causal relationship requires additional genetic, clinical, and functional evidence.

# Part J. 

## Short Reflection

### 1. What did the UCSC Cell Browser show you that the UCSC Genome Browser could not?

The UCSC Cell Browser showed how BRCA2 expression varies among different cell types in the human mammary gland. Unlike the UCSC Genome Browser, which provides information about genomic location, gene structure, and variants, the Cell Browser allowed visualization of gene expression at the single-cell level.

### 2. Why can the same gene have different expression levels among different cell types?

Gene expression varies because different cell types have distinct functions, regulatory mechanisms, and cellular activities. These differences influence when and how strongly genes are expressed according to each cell's biological needs.

### 3. Why should you be careful when interpreting a gene that shows zero or very low expression in single-cell data?

Zero or low expression does not necessarily mean that a gene is absent or biologically inactive. Single-cell RNA sequencing may fail to detect transcripts because of low RNA abundance, technical limitations, or differences in cellular activity. Therefore, undetected expression should not automatically be interpreted as a lack of gene function.

### 4. Why is it useful to combine information about genomic location, genetic variants, and cell-specific gene expression?

Combining these data provides a better understanding of how genetic changes may influence cellular functions and contribute to disease. For BRCA2, genomic information identifies its location and pathogenic variants, while single-cell expression data reveal which mammary gland cell types contain detectable BRCA2 transcripts. Together, these findings help connect genetic variation with biological function and disease susceptibility.

### 5. What was the most interesting observation you made about your assigned gene?

The most interesting observation was that BRCA2 showed detectable expression in only approximately 2.9% of the 11,375 mammary gland cells analyzed. Despite its important role in DNA repair and association with hereditary breast and ovarian cancer, its expression was low and scattered across several cell types. This demonstrates that a disease-associated gene does not necessarily have high detectable expression in the tissue associated with the disease.

# References

https://cells.ucsc.edu/?ds=tabula-sapiens+by-organ+mammary&label=cell_ontology_class&gene=BRCA2
https://cells.ucsc.edu/?ds=tabula-sapiens+by-organ+mammary&label=cell_ontology_class&gene=ADIRF
https://www.ncbi.nlm.nih.gov/clinvar/variation/873424/



