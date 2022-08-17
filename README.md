# Genelists compiled from various sources that can be used for geneset analysis in denovo or gene burden analysis

The gene lists in this repository were collected from multiple public databases and published papers (sources noted below). The lists are separated into constrained and original genes. The constraint score is determined by the observed/expected ratio (oe) of less than 0.35. The constrained genes were further categorized by Protein Truncated Variants (PTV), Missense and PTVMissense. The criteria filter for constrained missense variants is a missense Z (misZ) score of greater than 3.09. The criteria filter for constrained PTV variants is a probability of being loss-of-function intolerant (pLI) score of greater than and equal to 0.9. These scores were calculated using data from the Genome Aggregation Database (gnomAD, https://gnomad.broadinstitute.org/help/constraint). 


## The current genelists within this repository are listed below along with their sources:
### 1. Kidney genes (https://www.columbiamedicine.org/divisions/gharavi/resources.php)
	1. CPMG_kidney_gene_list.csv (625 genes)
### 2. Nephron Progenitor Cells (NPC) (https://journals.plos.org/plosbiology/article?id=10.1371/journal.pbio.3000152)
	1. NPCa_c_d_wk18_Top_decile.csv (2451 genes)
	2. NPCa_c_d_wk18_Top_decile_pli09_oe_lof_up_035_PTV_Constrained.csv (632 genes)
	3. NPCa_c_d_wk18_Top_decile_misZ3_09_Missense_Constrained.csv (238 genes)
	4. NPCa_c_d_wk18_Top_decile_pli09_oe_lof_up_035_ANDOR_misZ3_09_PTVMissense_Constrained.csv (663 genes) 
### 3. Autism (http://autism.mindspec.org/autdb/Welcome.do)
	1. AutismDB_gene_list.csv (1285 genes)
	2. AutismDB_constrained_genes.csv (1387 genes)
	3. AutismDB_pli09_oe_lof_up_035_PTV_Constrained.csv (547 genes)
	4. AutismDB_pli09_misZ309_Missense_Constrained.csv (265 genes)
	5. AutismDB_pli09_oe_lof_up_035_ANDOR_misZ309_PTVMissense_Constrained.csv (575 genes)
### 4. Congenital Heart Disease (CHD) (https://www.nature.com/articles/ng.3970)	
	1. CHD_gene_list.csv (253 genes) 
	2. CHD_constrained_genes.csv (251 genes)
	3. CHD_pli09_oe_lof_up_035_PTV_Constrained.csv (99 genes)
	4. CHD_misZ_309_Missense_Constrained.csv (46 genes)
	5. CHD_pli09_oe_lof_up_035_ANDOR_misZ309_PTVMissense_Constrained.csv (106 genes)
### 5. Schizophrenia (https://www.ncbi.nlm.nih.gov/pmc/articles/PMC9005191/#supp1)
	1. schizophrenia_gene_list.csv (738 genes)
	2. schizophrenia_gene_list_PTV_Constrained.csv (112 genes)
	3. schizophrenia_gene_list_Missense_Constrained.csv (49 genes)
	4. schizophrenia_gene_list_PTVMissense_Constrained.csv (118 genes)

