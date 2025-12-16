# Transcriptomic Profiling of Psoriatic Arthritis and Psoriasis Skin Lesions Reveals Shared and Distinct Gene Expression Signatures

This repository presents a transcriptomic analysis comparing skin biopsies from patients with Psoriatic Arthritis (PsA), Psoriasis (PsO), and healthy controls. The goal is to identify gene expression differences that may enable earlier, non-invasive diagnosis of PsA using skin biopsies.

## 📄 Files Included

- `PsO Project Report.pdf` – Full report including all figures, tables, methods, and interpretation  
- `R_Markdown_DESeq2_GSE186063.pdf` – RMarkdown output with code
- `PsO Project Presentation.pdf` – Slide deck summarizing key findings for presentation  

## 🔍 Project Overview

- **Dataset**: Public RNA-seq data from GEO [GSE186063](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE186063)  
- **Groups Compared**: Psoriasis (PsO), Psoriatic Arthritis (PsA), and Ankylosing Spondylitis (AS/CTL)  
- **Tools Used**:  
  - Preprocessing: FastQC, Trimmomatic, HISAT2, HTSeq (via Galaxy)  
  - Analysis: DESeq2, DAVID, EnhancedVolcano, pheatmap  
  - Visualization: R/Bioconductor, BioRender  

## 🧬 Key Findings

- No DEGs between PsO and PsA skin lesions, indicating similar transcriptomic profiles  
- Both PsO and PsA show strong upregulation of keratinization and immune-related genes compared to controls  
- PsO uniquely enriched for genes involved in neurodegenerative pathways (e.g., Alzheimer’s, Parkinson’s)  
- Elevated expression of **CALML5**, **CAMK2B**, and **CDK5R1** may indicate systemic effects beyond the skin

## 📂 Contents

| File | Description |
|------|-------------|
| `PsO Project Report.pdf` | Full research report with methods, results, discussion, figures, and tables |
| `R_Markdown_DESeq2_GSE186063.pdf` | DESeq2 analysis workflow and result visualizations |
| `PsO Project Presentation.pdf` | Slides for academic or professional presentation |

## 🔁 Reproducibility

All RNA-seq data were processed via the Galaxy platform. Downstream analysis was completed in R using the DESeq2 pipeline. The full workflow is documented in the RMarkdown output file.

## 🙏 Acknowledgments

- Data: Deng et al., GEO accession [GSE186063](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE186063)  
- Tools: Galaxy, Bioconductor (DESeq2, EnhancedVolcano), DAVID, BioRender

---

*This project was completed independently for academic purposes and is not affiliated with any institution or publication at this time.*
