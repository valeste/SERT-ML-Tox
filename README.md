# Molecular Docking and Machine Learning for Prioritizing Antidepressants in Aquatic Environments

### Project Overview

Contaminants of emerging concern (CECs) are increasingly detected in aquatic environments, including Puget Sound. Among these contaminants, antidepressants are of particular concern due to their frequent detection and potential to disrupt neurotransmitter regulation in aquatic organisms.

The __serotonin transporter (SERT)__ is a molecular target of several antidepressant classes, including selective serotonin reuptake inhibitors (SSRIs), serotonin-norepinephrine inhibitors (SNRIs), and tricyclic antidepressants (TCAs). Although SERT is highly evolutionarily conserved across vertebrates, species-specific structural differences may influence their interactions with environmental chemicals.

This project aims to develop a computational screening workflow that integrates __protein homology modeling, molecular docking, and machine learning__ to identify and prioritize environmental chemicals with potential SERT-inhibitory activity.

### Proposed Computational Workflow and Associated Databases + Softwares
1. Protein sequence and structure selection: [NCBI](https://www.ncbi.nlm.nih.gov/), [RCSB PDB](https://www.rcsb.org/), BLASTP, [Clustal Omega](https://www.ebi.ac.uk/jdispatcher/), [Jalview](https://www.jalview.org/)
2. Homology modeling and structural QA/QC: [SWISS-MODEL](https://swissmodel.expasy.org/) and built in SWISS-MODEL structural assessment tools (QMEANDisCo, MolProbity)
3. Development of machine learning training dataset
4. Molecular docking: [GOLD](https://www.ccdc.cam.ac.uk/solutions/software/gold/) and [GNINA](https://github.com/gnina/gnina)
5. Machine learning: [iML Studio](https://bioinformatics.uwb.edu/iml/)
6. Chemical prioritization using environmental chemical dataset (in development) 

### Project Status

*In development - Nov. 2026*

Initial work has focused on steps 1 and 2 of the "Proposed Computational Workflow" -- identifying putative Chinook salmon SERTa sequences, generating homology models from experimentally determined human SERT templates, and assessing structural quality prior to molecular docking.

## Relevant Literature

Chen, Yuan, Mingyuan Cao, Yongliang Yang, Han Zhang, and Jingwen Chen. “Zebrafish Serotonin Transporter Inhibition Enables Identification of Neuroactive Chemicals: Structural Insights into Interspecies Differences.” Environmental Science & Technology 60, no. 33 (2026): 23162–69. https://doi.org/10.1021/acs.est.6c04972. 

Yang, Fengyuan, Tingting Fu, Xiaoyu Zhang, et al. “Comparison of Computational Model and X-Ray Crystal Structure of Human Serotonin Transporter: Potential Application for the Pharmacology of Human Monoamine Transporters.” Molecular Simulation 43, nos. 13–16 (2017): 1089–98. https://doi.org/10.1080/08927022.2017.1309653. 
