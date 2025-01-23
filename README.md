# Bioinformatics and Network Medicine

This repository hosts the final project for the Bioinformatics and Network Medicine exam, instructed by Professors Paolo Tieri and Manuela Petti, as part of the Master’s degree in Data Science at Sapienza University of Rome. The project demonstrates our group's collective efforts and key findings.

-------------------------------------------------------------------------------------------------------------------------------------

### **Exam Structure**

The exam in Bioinformatics and Network Medicine consisted of an oral exam and a final project detailed in the document ***`BNM_project_ay_24_25.docx`***.<br>

The final project involved applying bioinformatics and network medicine techniques to identify putative disease genes and explore drug repurposing opportunities for retinal dystrophy (UMLS ID: C0854723). 

The workflow included:
1. **Data Gathering and Network Construction:** 
   - Protein-protein interaction data were retrieved from BioGRID, filtered for human physical interactions, and used to construct the interactome's largest connected component (LCC).
   - Disease-related genes were curated from GDA data, verified for consistency, and mapped onto the interactome to form the disease module.

2. **Algorithmic Analysis:**
   - Four network-based approaches (DIAMOnD, DiaBLE, a diffusion-based algorithm and PROCONSUL) were applied to predict putative disease genes. 
   - Algorithms were validated using performance metrics (precision, recall, F1-score) through 5-fold cross-validation.

3. **Enrichment and Drug Repurposing:**
   - Enrichment analysis (via EnrichR) assessed the overlap of pathways and biological functions between the original disease genes and predicted genes.
   - Drug-gene interactions were analyzed using DGIdb for the top-ranked putative genes to identify potential drug candidates, followed by validation through clinical trial searches.

While algorithm outputs exhibited limited overlap, the methods provided insights into disease module structure and highlighted potential gene candidates.
No approved drugs targeting the predicted genes were found in DGIdb, reflecting challenges in leveraging current databases for this disease.



-------------------------------------------------------------------------------------------------------------------------------------

### **Project Overview**

This project was a collaborative effort by [Francesco Mari](https://github.com/FraMari00), [Livia Oddi](https://github.com/Livia020799), [Lorenzo Pannacci](https://github.com/LorenzoPannacci).

-------------------------------------------------------------------------------------------------------------------------------------

### **Exam Score and Project Usage**

**This project (plus the oral exam) received an overall score of 30 out of 30**.<br> Feel free to use it as a reference if you are planning to take the exam in the upcoming years.<br> 
Please do not hesitate to contact us if you need further explanations or encounter any issues with the materials.
 
