#### Duke Breast Cancer Imaging

Notes / sites for studies:
- MRI-DCE: https://www.sciencedirect.com/topics/medicine-and-dentistry/dynamic-contrast-enhanced-mri
  - DCE-MRI has been established as a method to quantitatively evaluate tumor biology in terms of microcirculation and tumor response following therapy in vivo. DCE-MRI is performed by using the updated fast imaging sequences that are repeatedly applied over the entire coverage of tumor volume during the intravenous injection of a contrast agent. It consists of the rapid serial acquisition of MRI images during the injection of a contrast agent (CA; most often a gadolinium chelate). The CA acts by shortening the proton relaxation times of target tissues, which results in a change in the MR signal during data acquisition. After appropriate conversion to concentration, CA uptake curves are analyzed using either compartmental modeling or non-model based approaches to infer the extent and properties of tissue.

Technology / IT : 
NBIA download retriever - https://wiki.cancerimagingarchive.net/display/NBIA/Downloading+TCIA+Images

Readings and possible citations:
- https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6134102/
- Mednet - https://arxiv.org/ftp/arxiv/papers/2110/2110.06512.pdf

#### [Breast cancer digital repository](https://bcdr.eu/) - 
- A compilation of Breast Cancer anonymized patients' cases annotated by expert radiologists containing clinical data (detected anomalies, breast density, BIRADS classification, etc.), lesions outlines, and image-based features computed from Craniocaudal and Mediolateral oblique mammography image views. This Contains - 
- Digitalized Film mammography (BDCR-FM)
  - composed by 1010 (998 female and 12 male) patients cases (with ages between 20 and 90 years old), including 1125 studies
  - 3703 mediolateral oblique (MLO) and craniocaudal (CC) mammography incidences 
  - 1044 identified lesions clinically described (820 already identified in MLO and/or CC views)
- Full Field Digital mammography and related ultrasound images (BDCR-DM)
  - 724 (723 female and 1 male) Portuguese patients cases (with ages between 27 and 92 years old), including 1042 studies, 3612 MLO and/or CC mammography incidences and 452 lesions clinically described (already identified in MLO and CC views)
  - 818 segmentations were manually made and BI-RADS classified by specialized radiologists
  - MLO and CC images MLO and CC images with a resolution of - 
    - 3328 (width) by 4084 (height) or 2560 (width) by 3328 (height) 
    - bit depth - 14 bits per pixel
    - Format - TIFF
- Benchmarking datasets - four datasets (two masses-based and two microcalcifications/calcifications-based) representatives of benign and malignant lesions (biopsy-proven) comprising instances of clinical and image-based features
- Search criteria for downloads
  - Gender and Age 
  - Breast density and location
  - with or without segmentations
  - specific patient id
  - by mammography type (Normal/Anomaly, Nodule, Microcalcification/Calcification, Axillary Adenopathy, Distortion (Architectural/Stroma))
  - by biopsy result (Benign/suspect/Insufficient/Un-representative/malignant)
  - definitive diagnosis (Benign/C.I.S/Invasive C./Micro C./Others)
  - by BIRADS classification 
 - Displayed Metadata
   - Lesions 
   - segmentation - (oblique / cranium caudal)
     - various statistical metrics (Area/perimeter/kurtosis/std deviation/mode/)

#### [National Cancer Institute - Cancer Genome atlas program](https://www.cancer.gov/about-nci/organization/ccg/research/structural-genomics/tcga)
- Contains 2.5PB+ of genimic, epigenomic, transcriptomic and proteomic data 
- fully public and open source downloadable MAF formatted (tab-delimited text file with aggregated mutation) data
- Data is broadly categorized by files and cases
- Filtration criteria for files
  - Data category - (simple nucleotide variation/sequencing reads/structural variation/copy number variation/transcriptome profiling/biospecimen/structural variation/dna methylation/clinical/proteome profiling/somatic structural variation/combined nucleotide variation)
  - Data Type (Annotated Somatic Mutation/Raw Simple Somatic Mutation/Masked annotated somatic mutation/Aggregated somatic mutation/Masked somatic mutation)
  - Experimental strategy (WXS/Targeted sequencing/WGS)
  - Workflow type (GEnie simple somatic mutation/MuSE Annotation/MuTect2 Annotation/SomaticSniper annotation/Varscan2 annotation)
  - Data format (vcf/maf)
- Terms 
  - [Mutation Annotation Format (MAF)](https://docs.gdc.cancer.gov/Data/File_Formats/MAF_Format/#:~:text=Mutation%20Annotation%20Format%20(MAF)%20is,(or%20open%2Daccess).) is a tab-delimited text file with aggregated mutation information from VCF Files and are generated on a project-level
- Filtration criteria for cases
  - Primary site (i,e location of the body i,e bronchus, colon, spinal cord..)
  - Program and NCI Project
  - Disease type 
  - Gender
  - Age / vital status or ethnicity
 - NIC/TGCA provides 3 kinds of analyses that includes 
   - venn diagram based set operations
   - coort comparison
   - clinical analysis - graphs and interactive bar charts by demographics, survival, ethnicity, gender, race, age and primary diagnosis 
 - Data exploration feature by cases, clinical, genes and mutations with - 
   - pie charts depicting distribution by project, disease type, gender and vital status 
   - Available files by data category + mutations,genes etc by caseid and project for various body location (primary site) 
- Which research and how would they be useful?

[International Cancer Genome Consortium](http://icgc.org), [(Data portal)](http://dcc.icgc.org/)
* Provides cancer data sets 
